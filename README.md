# master-docker

## Source Code Terminal
### push docker
```
docker-compose up -d
```
```
docker-compose build --no-cache
```

### Stop Docker
```
docker-cpmpose down
```

### restore database
```
docker exec -i prototype_api-db-1 pg_restore -U postgres -d nama_database /docker-entrypoint-initdb.d/nama_database.sql
```

