
# django2.0-redis.
环境django2.0 python3.4 redis 3.2.1

用法：

import redis (pip install first)

pool = redis.ConnectionPool(host='localhost', port=6379, db=0)

c = redis.Redis(connection_pool=pool)

c.set(ran, r1)
