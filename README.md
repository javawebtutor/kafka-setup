# kafka and zookeeper setup
- Running zookeeper:

Add beloow entry in server.properties file located under config folder.
  listeners=PLAINTEXT://localhost:9092
  auto.create.topics.enable=false

Use below command to run zookeeper.

  C:\kafka\kafka_2.12-2.6.0>.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
  
- Running Kafka Server:
Use below command to run kafka.

  C:\kafka\kafka_2.12-2.6.0>.\bin\windows\kafka-server-start.bat .\config\server.properties
