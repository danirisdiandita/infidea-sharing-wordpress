# Wordpress - Full stack docker-compose file

1. wordpress app
2. phpmyadmin
3. postgre

# Build & Run 
set the external ports by updating `docker-compose.yml` 
then build & run 
```
docker-compose up --build
```

to stop docker container and remove volume
```
docker-compose down --volume
```