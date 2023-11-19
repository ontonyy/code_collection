### Connect to RedisInsight via docker for connect to own redis database
`docker run -v redisinsight:/db -p 8001:8001 redislabs/redisinsight:latest`

Either for connecting via docker-compose check same named file name in current directory and run in terminal `docker compose up`

### Connect to redis-stack via docker
-> `docker run -d --name redis-stack -p 6379:6379 -p 8001:8001 redis/redis-stack:latest`

-> Connect to redis-cli `docker exec -it redis-stack redis-cli`