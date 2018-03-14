# Django by example

[TOC]

## 1. Building a Bolg Application
* 安装Django并创建你的第一个项目
* 设计模型（models）并且生成模型（model）数据库迁移
* 给你的模型（models）创建一个管理站点
* 使用查询集（QuerySet）和管理器（managers）
* 创建视图（views），模板（templates）和URLs
* 给列表视图（views）添加页码
* 使用Django内置的视图（views）
`os=win7 python=2.7 django=1.8.6` 

+ virtualenv

`pip install virtualenv`

`pip install virtualenvwrapper-win    # 管理虚拟环境`

[参考](http://www.jianshu.com/p/dcfe4cab4933)

`virtualenv --no-site-packages my_env`

`source ~/my_env/bin/activate  # linux`

`my_env/Scripts/activate #windows`

activate.bat  (start the virtualenv)

deactivate    (stop the virtualenv)

`workon tudj`

* Install Django 

`python install django==1.8.6`

```python
    >>> import django
    >>> django.VERSION
    DjangoVERSION（1, 8, 5, 'final', 0)
```
```python
    django-admin startproject mysite    #创建项目 
    django-admin startapp blog          #创建应用
    python manage.py makemigratetion #create a table
    
    python manage.py runserver 8080 # you can change the default port
```

### 设计blog数据架构

    python manage.py makemigrations blog    #数据库迁移

    python manage.py sqlmigrate blog 0001   #迁移内容

    python manage.py migrate                #同步数据库

    python manage.py createsuperuser        #创建超级用户

TIME_ZONE = 'Asia/Shanghai'

+ 中文乱码解决

```python
    import sys;
    reload(sys);
    sys.setdefaultencoding("utf8")
```

### 使用查询集（QuerySet）和管理器（managers）

    python manage.py shell

```python

    from django.contrib.auth.models import User
>>> from blog.models import Post
>>> user = User.objects.get(username='admin')
>>> post = Post.objects.create(title='One more post',
                        slug='one-more-post',
                        body='Post body.',
                        author=user)
>>> post.save()
    post.title = 'New title'
>>> post.save()
    all_posts = Post.objects.all()
    Post.objects.all()
    Post.objects.filter(publish__year=2015) #过滤
    Post.objects.filter(publish__year=2015, author__username='admin')
    Post.objects.filter(publish__year=2015).filter(author__username='admin')    #与上一句效果一样
    Post.objects.filter(publish__year=2015).exclude(title__startswith='Why')    #排除
    Post.objects.order_by('title')  #升序
    Post.objects.order_by('-title') #降序
    post = Post.objects.get(id=1)
    post.delete() #删除记录

```

### Building list and detail views

    EMAIL_HOST = 'smtp.163.com'
    EMAIL_HOST_USER = 'cutewxy@163.com'
    EMAIL_HOST_PASSWORD = '83410922'
    EMAIL_PORT = '25'
    EMAIL_USE_TLS = True

>>> from django.core.mail import send_mail
>>> send_mail('Django mail', 'This e-mail was sent with Django.', 'cutewxy@163.com', ['282321538@qq.com'], fail_silently=False)

### Add Tags

``` python
>>> from blog.models import Post
>>> post = Post.objects.get(id=1)
>>> post.tags.add('music', 'jazz', 'django')
>>> post.tags.all()
[<Tag: jazz>, <Tag: music>, <Tag: django>]
>>> post.tags.remove('django')
>>> post.tags.all()
[<Tag: jazz>, <Tag: music>]
```

## 2. Enhancing Your Blog with Advanced Features

* 给用户创建一个表单来填写他们的姓名，email，收件人以及评论，评论不是必选项。
* 在*views.py*文件中创建一个视图（view）来操作发布的数据和发送email
* 在blog应用的*urls.py*中为新的视图（view）添加一个URL模式
* 创建一个模板（template）来展示这个表单

## 3:Extending Your Blog Application

* templatetags
由于创建 init.py 文件名错误，以为代码错误。更改为 `__init__.py`

\_\_init\_\_.py

* 修改setting.py,不要忘了 **SITE_ID = 1**
* 用内置的Jetty web服务运行Solr
```
  java -jar start.jar
  python manage.py rebuild_index
```
## 4.