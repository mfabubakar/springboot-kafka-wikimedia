# springboot-kafka-wikimedia
periswamy subramanyan

https://drive.google.com/drive/folders/1hd5WFGL3XFu6Rw8-DxdptjXv9LLQkwdq

------------
apache kafka download - 

https://kafka.apache.org/documentation/#quickstart

STEP 1: GET KAFKA
get started ->Quick start ->Download -> unzip and rename to kafka

STEP 2: START THE KAFKA ENVIRONMENT

1) Start Zookeeper 
cd kafka 
>>
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

2) Open another terminal session and run:

>>
.\bin\windows\kafka-server-start.bat .\config\server.properties

Once all services have successfully launched, 
you will have a basic Kafka environment running and ready to use.

-----------

create a springboot project 
1. web depedenct
2. spring apche kafka
	
pushlich message to topic -->
---
STEP 5: READ THE EVENTS from topic

>>
.\bin\windows\kafka-console-consumer.bat --topic javaguides_json --from-beginning --bootstrap-server localhost:9092
This is my first event
This is my second event

------------------------
.\bin\windows\kafka-console-consumer.bat --topic wikimedia_recentchange --from-beginning --bootstrap-server localhost:9092

