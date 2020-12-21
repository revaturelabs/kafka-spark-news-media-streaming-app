# kafka-spark-news-media-streaming-app

## To Test Kafka Services

1. Startup zookeeper 
```
$ bin/zookeeper-server-start.sh config/zookeeper.properties
```
2. Start kafka broker
```
$ bin/kafka-server-start.sh config/server.properties
```

3. Join the topic 
- option 1: from beginning
- option 2: from connection point, going forwards

4. Produce to the topic:
- option 1: from json file
- option 2: from RDBMS

