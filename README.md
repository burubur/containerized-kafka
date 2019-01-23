# Containerized Kafka

This is an experimental Kafka using Docker, so we can deploy it as a container and we can access it through a defined IP.
Here are some of exported IP:

- **Zookeeper**: 22181
- **Kafka**: 29092
- **Kafka Manager**: 29000, yes you can access it through your favorite browser on this url -> [localhost:29000](localhost:29000)

## How to Run

```sh
docker-compose up -d
```

---