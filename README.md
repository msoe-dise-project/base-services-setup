# base-service-setup
Uses Docker Compose to run various base services

Current services include:

* Apache Cassandra (ports 9042 and 9160)
* Apache Kafka (port 9092)
* Docker Registry (port 5000)
* Minio (ports 9000 and 9001)
* Portainer (port 9443)
* Postgres (port 5432)
* Redis (port 6379)

You will need to have docker engine and docker compose installed.

To start the services run:

```bash
$ docker compose up -d
```

To shut the services down:

```bash
$ docker compose down
```

Portainer is installed and can be used to view the statuses of and manage the services.  Point your web browser at [localhost:9443](https://localhost:9443).
