# airflow-on-docker-compose for AirFlow version 1.10.x (Not AirFlow 2.0)

Refer: https://github.com/troszok/airflow-on-docker-compose

On Mac, create .env file:
```
echo -e "AIRFLOW_UID=$(id -u)\nAIRFLOW_GID=0" > .env
```

To stand-up the AirFlow with LocalExecutor:
```
docker-compose up -d
```

Login to localhost:8080
