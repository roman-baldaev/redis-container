# redis-container
Basic docker for Redis, with data mounted for dumps and config.

Example of `.env` file:
```
REDIS_STACK_SERVER_PORT=6379
REDIS_PASSWORD=verystrongpassword
```

If you want to use a redis configuration file (`redis/redis.conf`), uncomment the corresponding line in `docker-compose.yml` file.
