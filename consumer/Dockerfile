FROM openjdk
WORKDIR /Assignment
COPY kafka/ /Assignment/

ENTRYPOINT ["./bin/kafka-console-consumer.sh","--bootstrap-server","server:9092","--from-beginning","--topic" ]

CMD  [ "test" ]