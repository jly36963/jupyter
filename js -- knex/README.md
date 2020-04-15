# knex notes -- jupyter

* To set up DBs, run the following commands:
    * `docker volume create mongodata_jupyter`
    * `docker volume create pgdata_jupyter`
* To run DBs, run this command:
    * `docker-compose -f docker-compose.db_only.yml up --build`
    