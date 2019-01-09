# mynotes
https://hackernoon.com/10-data-structure-algorithms-and-programming-courses-to-crack-any-coding-interview-e1c50b30b927


kakfa :
kafka-console-producer --broker-list 127.0.0.1:9092 --topic first_topic --property parse.key=true --property key.separator=,
> key,value
> another key,another value

kafka-console-consumer --bootstrap-server 127.0.0.1:9092 --topic first_topic --from-beginning --property print.key=true --property key.separator=,

KafkaCat (https://github.com/edenhill/kafkacat) is an open-source alternative to using the Kafka CLI, created by Magnus Edenhill.

While KafkaCat is not used in this course, if you have any interest in trying it out, I recommend reading: https://medium.com/@coderunner/debugging-with-kafkacat-df7851d21968

configure producer: https://kafka.apache.org/documentation/#producerconfigs

configure consumers:  https://kafka.apache.org/documentation/#consumerconfigs

https://docs.confluent.io/current/streams/developer-guide/test-streams.html#streams-developer-testing



https://medium.com/@stephane.maarek/the-kafka-api-battle-producer-vs-consumer-vs-kafka-connect-vs-kafka-streams-vs-ksql-ef584274c1e

https://lombardo-chcg.github.io/tools/2017/12/20/kafka-log-compaction.html

https://github.com/simplesteph/kafka-connect-github-source
