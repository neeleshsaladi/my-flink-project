# Apache Flink 

![image1](https://res.infoq.com/presentations/sql-streaming-apache-flink/en/slides/sl3-1529543225417.jpg)

## Neelesh Saladi

## Demonstration Skill:
- In this Flink project I worked on configuring flink on my windows using intellij as the IDE.

## Prerequisites:
- [Apache Flink Latest version](https://flink.apache.org/downloads.html#apache-flink-1121)
- Java jdk installed
- Maven
- IntelliJ IDE


## Introduction to Kafka
- You can instal kafka by clicing on the following [link](https://kafka.apache.org/downloads) 
- After download is completed, you can get a tar file. Extract the tar file by useing command 
1. tar -xzf kafka_2.13-2.7.0.tgz
2. cd kafka_2.13-2.7.0
- After that you need to set the environment variable under KAFKA_HOME with C:\kafka_2.13-2.7.0

## Kafka set up using Maven
- To demonstrate I'm creating a project using maven in IntelliJ IDE.
- You need to slect the Maven in the
 left pane and java version on the start screen. Now click on finish
 ![image1](https://github.com/Sindhujav18/flink-kafka-java/blob/main/int1.png)

- Next, you need to select the name of the project, which will be the artifact id and click on finish.
![image2](https://github.com/Sindhujav18/flink-kafka-java/blob/main/int2.png)
- Now, you need to add dependencies to pom.xml file, there are some mandotory dependencies that you need to add.
![image3](https://github.com/Sindhujav18/flink-kafka-java/blob/main/int3.png)
- Demonstration Video: https://app.vidgrid.com/view/0POsipXWwQ6Q

## Basic commands to use kafka
- To start Kafka environment
---
``bin/zookeeper-server-start.sh config/zookeeper.properties``

``bin/kafka-server-start.sh config/server.properties``

## References
- https://www.tutorialspoint.com/apache_kafka/apache_kafka_installation_steps.htm 
- https://kafka.apache.org/quickstart 
