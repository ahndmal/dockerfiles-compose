# dockerfiles-compose

Examples of Dockerfile(s) and Docker-Compose files for deploment.


```cli
docker run -d -p 5432:5432 --name postgres136 -e POSTGRES_PASSWORD=secret postgres:13.6-alpine
```


```cli
docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=secret -d mysql:tag
```
