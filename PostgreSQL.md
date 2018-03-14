<span id="menu">Menu</span>

[TOC]

## 基本命令
* 初次安装后，默认生成一个名为postgres的数据库和一个名为postgres的数据库用户
```python
pip install psycopg2
```

### [settings.py配置](#menu)
```
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
### [新建用户、数据库、获取权限](#menu)
```
psql -U postgres
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
### [登陆数据库](#menu)
```
λ psql -U jzycc -d ccdb -h 127.0.0.1 -p 5432
# -U指定用户，-d指定数据库，-h指定服务器，-p指定端口
用户 jzycc 的口令：
psql (9.6.5)
输入 "help" 来获取帮助信息.

ccdb=>
```
### 导入导出数据

#### Navicat premium 导入向导

> csv 文件有中文时,选择UTF8编码时,会显示乱码
>
> 选择`10008 (MAC - Simplified Chinese GB 2312)`编码
>
> 以此编码导入也能解决timestamptz类型格式的时间类型显示错误



#### 未曾验证 psql

```
 copy public.callcenter_recordinglist (filename, record_date, record_time, call_type, call_id, source_number, workno, line_id, length, status, location, workname, path, start_record_time, agent_id, cti_connect_number, domain, end_time, begint_ime) FROM 'D:/Work/Yunzx/Database/SQLServer2005/store.csv' DELIMITER ',' CSV HEADER ENCODING 'ISO_8859_5' NULL AS '';
```
## [数据类型](#menu)
### [数值数据类型](#menu)

| 名称        | 描述                 | 存储大小 | 范围                                       |
| --------- | ------------------ | ---- | ---------------------------------------- |
| smallint  | 存储整数，小范围           | 2字节  | -32768 至 +32767                          |
| integer   | 存储整数使用这个类型可存储典型的整数 | 4字节  | -2147483648 至 +2147483647                |
| bigint    | 存储整数，大范围           | 8字节  | -9223372036854775808 至 9223372036854775807 |
| decimal   | 用户指定的精度，精确         | 变量   | 小数点前最多为131072个数字; 小数点后最多为16383个数字。       |
| numeric   | 用户指定的精度，精确         | 变量   | 小数点前最多为131072个数字; 小数点后最多为16383个数字。       |
| real      | 可变精度，不精确           | 4字节  | 6位数字精度                                   |
| double    | 可变精度，不精确           | 8字节  | 15位数字精度                                  |
| serial    | 自动递增整数             | 4字节  | 1 至 2147483647                           |
| bigserial | 大的自动递增整数           | 8字节  | 1 至 9223372036854775807                  |

### [字符串数据类型](#menu)

String数据类型用于表示字符串类型值。

| 数据类型                    | 描述                                       |
| ----------------------- | ---------------------------------------- |
| char(size)              | 这里**size**是要存储的字符数。固定长度字符串，右边的空格填充到相等大小的字符。 |
| character(size)         | 这里**size**是要存储的字符数。 固定长度字符串。 右边的空格填充到相等大小的字符。 |
| varchar(size)           | 这里**size**是要存储的字符数。 可变长度字符串。             |
| character varying(size) | 这里**size**是要存储的字符数。 可变长度字符串。             |
| text                    | 可变长度字符串。                                 |

### [日期/时间数据类型](#menu)

  * 日期/时间数据类型用于表示使用日期和时间值的列。

| 名称                         | 描述          | 存储大小 | 最小值           | 最大值           | 解析度      |      |
| -------------------------- | ----------- | ---- | ------------- | ------------- | -------- | ---- |
| timestamp [ (p) ] [不带时区 ]  | 日期和时间(无时区)  | 8字节  | 4713 bc       | 294276 ad     | 1微秒/14位数 |      |
| timestamp[ (p) ]带时区        | 包括日期和时间，带时区 | 8字节  | 4713 bc       | 294276 ad     |          |      |
| date                       | 日期(没有时间)    | 4字节  | 4713 bc       | 5874897 ad    | 1微秒/14位数 |      |
| time[ (p) ] [ 不带时区 ]       | 时间(无日期)     | 8字节  | 00:00:00      | 24:00:00      | 1微秒/14位数 |      |
| time[ (p) ] 带时区            | 仅限时间，带时区    | 12字节 | 00:00:00+1459 | 24:00:00-1459 | 1微秒/14位数 |      |
| interval[ fields ] [ (p) ] | 时间间隔        | 12字节 | -178000000年   | 178000000年    | 1微秒/14位数 |      |

### [一些其他数据类型](#menu)

* 布尔类型：

| 名称      | 描述                | 存储大小 |      |
| ------- | ----------------- | ---- | ---- |
| boolean | 它指定true或false的状态。 | 1字节  |      |

* 货币类型：

| 名称    | 描述   | 存储大小 | 范围                                       |      |
| ----- | ---- | ---- | ---------------------------------------- | ---- |
| money | 货币金额 | 8字节  | -92233720368547758.08 至 +92233720368547758.07 |      |

* 几何类型：

几何数据类型表示二维空间对象。最根本的类型：点 - 形成所有其他类型的基础。

| 名称      | 存储大小     | 表示           | 描述                |      |
| ------- | -------- | ------------ | ----------------- | ---- |
| point   | 16字节     | 在一个平面上的点     | (x,y)             |      |
| line    | 32字节     | 无限线(未完全实现)   | ((x1,y1),(x2,y2)) |      |
| lseg    | 32字节     | 有限线段         | ((x1,y1),(x2,y2)) |      |
| box     | 32字节     | 矩形框          | ((x1,y1),(x2,y2)) |      |
| path    | 16+16n字节 | 封闭路径(类似于多边形) | ((x1,y1),…)       |      |
| polygon | 40+16n字节 | 多边形(类似于封闭路径) | ((x1,y1),…)       |      |
| circle  | 24字节     | 圆            | <(x，y)，r>(中心点和半径) |      |

## Server SQL 2008 数据迁移

* 直接导出SQL文件,datatime的数据类型(`CAST(0x00009E0E0095524F AS DateTime)`)无法直接插入Postgresql
* 查询的数据可以保存为txt文件,也可以直接复制到excel,另存为csv文件.
* 数据复制到excel,由于某些数据的值比较在大,或者是时间类型的,要先调整对比好,再另存为CSV文件
* 最好使用Navicat Preimun导入数据