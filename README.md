# kafkademo
Projeto simples para treinar os conceitos básicos do kafka.

Comandos importantes do kafka:

subir o zookeeper : zookeeper-server-start.sh /home/mcv/kafka/config/zookeeper.properties


subir o kafka : kafka-server-start.sh /home/mcv/kafka/config/server.properties


criar uma mensagem no consumer : kafka-console-producer.sh --broker-list  localhost:9092 --topic testejava


criar um tópico : kafka-topics.sh --bootstrap-server localhost:9092 --create --topic testejava --partitions 4
