# Docker Images

A repository of docker compose files to remember the most common Docker images.

## PostgreSQL and PG Admin

### Running Docker command

```docker
docker-compose -f pg-pgadmin.yml up --build
```

### Setting up the server in PGAdmin

```
Name: postgres
Host name/address: postgres
Port: 5432
Maintenance database: postgres
Username: postgres
Password: postgres
```

https://gist.github.com/jexchan/2351996
