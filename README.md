# Confluent `v3.0.1` Containeres

``` bash
docker-compose up
docker-compose down --volumes --remove-orphans
```

Service ports listening on `localhost`:

- 2181: Zookeeper;
- 8082: Rest-Proxy (Kafka-Rest);
- 9021: Control Center;
- 9092: Kafka;
- 18081: Schema Registry;

For more containers, have a look on [ConfluentInc](https://hub.docker.com/u/confluentinc) at Docker Hub.

