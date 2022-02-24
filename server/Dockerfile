FROM openjdk
WORKDIR /Assignment
COPY kafka/ /Assignment/
EXPOSE 9092

CMD [ "./bin/kafka-server-start.sh","config/server.properties" ]
