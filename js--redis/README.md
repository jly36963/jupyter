# redis notes -- jupyter

* To set up Redis volume, run the following commands:
    * `docker volume create redisdata_jupyter`
* To run Redis instance, run this command:
    * `docker-compose -f docker-compose.redis_only.yml up --build -d`
    