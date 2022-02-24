FROM openjdk
WORKDIR /Assignment
COPY kafka/ /Assignment/

ENTRYPOINT ["./bin/kafka-console-producer.sh","--bootstrap-server","server:9092","--topic"]
CMD [ "test" ]
