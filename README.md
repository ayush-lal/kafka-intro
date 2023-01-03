# Kafka Intro

# What is Apache Kafka?

- Apache Kafka is an open source distributed streaming platform
- Kafka aids in decoupling application through Producers and Consumers
- Producers and Consumers communicate events through Topics
- Topics are created in Brokers which are essentially individual running instances of Kafka
- Kafka is highly scalable and available through replication of Topics

# Docker Setup

```
curl --silent --output docker-compose.yml https://raw.githubusercontent.com/confluentinc/cp-all-in-one/6.1.1-post/cp-all-in-one/docker-compose.yml

docker-compose up -d
```
