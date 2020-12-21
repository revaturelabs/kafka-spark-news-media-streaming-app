# kafka-spark-news-media-streaming-app

Asana project page - [link](https://app.asana.com/0/1199601898942967/1199602323289561)
Github repo - [link](https://github.com/revaturelabs/kafka-spark-news-media-streaming-app)

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


---
# Working log

12/21/20:    
- Research JSON schema types for news/media articles
- Source sample-data JSON format (from Apple news).
- Convert /kafka-samples from pj3 repo - [link](https://github.com/revaturelabs/201005-reston-bigdata/tree/main/docs/tech)
  - Producer.scala 
  - Consumer.scala
  - Redirector.scala
  - config file
- Research Kafka security, spec. how to auth consumers

Before 12/20/2020:    
- Sketch out idea
- Create git repo
- Create asana project

