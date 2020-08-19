# rabbitmq-docker-template
## RabbitMQ Docker Template
Clone locally run docker-compose up -d to start up

### Accessing RabbitMQ Management Console
browse [http://localhost:15672/](http://localhost:15672/ "RabbitMQ Management Console") with the below

```console
Username : admin
Password : admin123
```
Of course, please make sure to change the current admin password immediately once you have confirmed the RabbitMQ and management console are running.


### Start up
```console
docker-compose up -d
```
### Stop and keep the data
```console
docker-compose down
```

### Stop and remove the data volume
```console
docker-compose down -v
```

