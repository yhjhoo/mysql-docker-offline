# mysql-docker-offline

to use: 


```
cat dockera* > mysql.tar.gz
tar zvxf mysql.tar.gz
docker load -i mysql.docker
```

mysql server: mysql:8.0.31

docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql
