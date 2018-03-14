[TOC]

# Django学习笔记

## 案例

```python
class importrecord(View):
    def get(self, request):
        # txt有多条数据,但最后只插入了一条数据,因为video=Video()只实例化了一个
        data = importdatabase('D:/Catalog/Django/maxone/apps/utils/sex.txt')
        # 放到for循环里面 或者 video = Video(lesson_id=6, name = dictdata['title'],url = dictdata['video'])
        video = Video()
        for dictdata in data:
            video.lesson_id = 6
            video.name = dictdata['title']
            video.url = dictdata['video']
            video.save()
        return render(request, "org_list.html",
                           {
                           }
               )
```

## 访问
* settings.py设置
  `ALLOWED_HOSTS = [192.168.1.130]`

* 启动服务机器的IP加上Port,如下
  `python manage.py runserver 0.0.0.0:8080 #启动服务`
  `192.168.1.130:8080 #客户端访问`


> <http://blog.csdn.net/yangmingqian/article/details/54691598>

## QuerySet

### [判断queryset是否为空](https://www.douban.com/note/301166150/)

1. `if queryset:pass`

2. `if queryset.count>0:pass`

3. `if queryset.exists():pass`

> 三种方式性能依次提升。

### exact(精确匹配)

```python
Entry.objects.get(headline__exact="Man bites dog") # '__' is two
```

将生成下面的SQL

```sql
SELECT ... WHERE headline = 'Man bites dog';
```

### iexact(精确匹配,忽略大小写)

## 命令

1. 清空数据库数据

  `python manage.py flush#Removes ALL DATA from the database`

## Packages

### virtualenv
```python
pip install virtualenv	# 生成虚拟环境
```

[virtualenvwrapper参考](http://www.jianshu.com/p/dcfe4cab4933)

`virtualenv --no-site-packages my_env`

`source ~/my_env/bin/activate  # linux`

`my_env/Scripts/activate #windows`

activate.bat  (start the virtualenv)

deactivate    (stop the virtualenv)

`workon tudj`

### virtualenvwrapper-win

>  virtualenvwrapper 是 virtualenv的管理工具，需先安装vintualenv

```python
pip install virtualenvwrapper-win	# 管理虚拟环境
```
添加windows环境变量 WORKON_HOME 和相应路径

```python
mkvirtualenv <name>    #创建虚拟环境
lsvirtualenv    #列出已有虚拟环境
rmvirtualenv <name>    #删除虚拟环境
workon <name>    #启动虚拟环境
deactivate    #关闭虚拟环境
```

### xadmin

* No module named future.utils

  `pip install future`


*  No module named six

  `pip install six`


*  No module named import_export.admin

  `pip install django-import-export`

## DataBase

### postgresql

```python
pip install psycopg2    # python 连接PostgreSQL数据库接口
```
* psql
```
psql -U postgres -d postgres
用户 postgres 的口令：
psql (9.6.5)
输入 "help" 来获取帮助信息.

postgres=# create user sa with password 'sa';
CREATE ROLE
postgres=# create database callcenter owner sa;
CREATE DATABASE
postgres=# grant all privileges on database callcenter to sa;
GRANT
postgres=# \q
```

## settings.py

- Database

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql_psycopg2',
        'NAME': 'pgtest_db',
        'USER': 'postgres',
        'PASSWORD': 'ksiniba22',
        'HOST': '127.0.0.1',
        'PORT': '5432',
    }
}
```

* Path

  > templates

  > `os.path.join(BASE_DIR, 'templates')`

  > css

  > `STATICFILES_DIRS = [os.path.join(BASE_DIR, 'static'),]`

  > 将app或第三方库移动到apps文件夹

  > `sys.path.insert(0, os.path.join(BASE_DIR,'apps'))`

* USE_TZ

  > 如果为True,影响数据库查询时报错.'year is out of range',
  >
  > 建议设置为`USE_TZ = False`
  >
  > 参考
  >
  > [django时间的时区问题](http://www.cnblogs.com/alan-babyblog/p/5739004.html)
  >
  > [关于django时区设置的问题](https://www.2cto.com/kf/201211/166500.html)


