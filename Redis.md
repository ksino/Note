# [Redis](https://redis.io/ "官网")
* Reids 并不支持windows, [Lear More](https://github.com/MicrosoftArchive/redis)
* download zip 后，建议放在D盘，C盘可能会因为权限的问题打不开文件
* start service
  redis-server.exe redis.windows.conf
* test
```
  redis-cli.exe -h 127.0.0.1 -p 6379
  127.0.0.1:6379> set age 21
  OK
  127.0.0.1:6379> get age
  "21"
  127.0.0.1:6379>
```
* pip install redis
* pip install hiredis # need to install VCForPython27
* [参考](http://blog.csdn.net/xiongchun11/article/details/68483659)

```python
pool = redis.ConnectionPool(host='127.0.0.1', port=6379)
r = redis.Redis(connection_pool=pool)
r.set('one', 'first')
r.set('two', 'second')
print r.get('one')
print r.get('two')
```

* 缓存、队列
* string
  set key
  get key
  incr key  # auto add 1
  incrby key increment
  decr key
  decrby key
  incrbyfloat key float
  append key value
  strlen key
  mset key value
  mget key

* hash
  hset key field value
  hget key field
  hmset key field value [field value ...]
  hmget key field [field ...]
  hgetall key

* List
  lpush
  rpush
  lpop
  rpop
  llen
* set
* zset
* multi
* watch
* expire
* ttl
* persist
