# Kafka Practice

## About Apach Kafka
* Your company is maintaining ,ultiple systems to queue the data, all of which has its bugs and limitations. You need a single centralized system that allows for publishing generic types of data, which will grow as your business grows. Kafka is <b>a publish/subscribe messaging system</b> designed to solve this problem.
* [Technical Document][2]
### Components
* Messages & Batches
* Schemas - consistent data format is important in Kafka
* Topics & Partitions
* Producers & Consumers
* Brokers & Clusters
  * a broker is a single Kafka server
  * multiple Clusters is better
### Tools
* Zookeeper: It stores the metadata for Kafka cluster and consumer 
* Kafka Broker (server)
### [Clients written in other languages][1]
* The clients are like APIs used to interact with Kafka

[1]:https://cwiki.apache.org/confluence/display/KAFKA/Clients
[2]:http://kafka.apache.org/documentation.html#gettingStarted
