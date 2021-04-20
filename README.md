# Apache Flink 

![image1](https://res.infoq.com/presentations/sql-streaming-apache-flink/en/slides/sl3-1529543225417.jpg)

## Neelesh Saladi

## Demonstration Skill:
- In this Flink project I worked on configuring flink on my windows using intellij as the IDE.

## Prerequisites:
- [Apache Flink Latest version](https://flink.apache.org/downloads.html#apache-flink-1121)
- Java jdk installed
- [nmap- Network Mapper](https://nmap.org/download.html)
- [IntelliJ IDE](https://www.jetbrains.com/idea/download/#section=windows)


## Introduction to Flink
-
- After download is completed, you can get a tar file. Extract the tar file by useing command 
1. tar -xvf flink-1.12.1-bin-scala_2.11.tgz
2. cd flink-1.12.1
- After that you need to set the environment variable under Flink_HOME with C:\flink-1-12.1

## Flink set up using Maven
- To demonstrate I'm creating a project using maven in IntelliJ IDE.
- You need to slect the Maven in the
 left pane and java version on the start screen. Now click on finish
 ![image1](https://github.com/Sindhujav18/flink-kafka-java/blob/main/int1.png)

- Next, you need to select the name of the project, which will be the artifact id and click on finish.
![image2](https://github.com/neeleshsaladi/my-flink-project/blob/main/Screenshot%20(23).png)
- Now, you need to add dependencies to pom.xml file, there are some mandotory dependencies that you need to add.
![image3](https://github.com/neeleshsaladi/my-flink-project/blob/main/Screenshot%20(26).png)
- After this I created a java sample code in which I did the character count with the flink configuration and it is successfully running with the Network mapper server.
![image3](https://github.com/neeleshsaladi/my-flink-project/blob/main/Screenshot%20(24).png)
- OUtput of my code when I run it.
![image3](https://github.com/neeleshsaladi/my-flink-project/blob/main/Screenshot%20(25).png)

## Demonstration Video: https://app.vidgrid.com/view/nNBHJcTtiv7J

## References
- https://ci.apache.org/projects/flink/flink-docs-release-1.9/getting-started/tutorials/flink_on_windows.html
- http://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism.html#Dependency_Scope
