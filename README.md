# mynotes
https://hackernoon.com/10-data-structure-algorithms-and-programming-courses-to-crack-any-coding-interview-e1c50b30b927


kakfa :
kafka-console-producer --broker-list 127.0.0.1:9092 --topic first_topic --property parse.key=true --property key.separator=,
> key,value
> another key,another value

kafka-console-consumer --bootstrap-server 127.0.0.1:9092 --topic first_topic --from-beginning --property print.key=true --property key.separator=,

KafkaCat (https://github.com/edenhill/kafkacat) is an open-source alternative to using the Kafka CLI, created by Magnus Edenhill.

While KafkaCat is not used in this course, if you have any interest in trying it out, I recommend reading: https://medium.com/@coderunner/debugging-with-kafkacat-df7851d21968
