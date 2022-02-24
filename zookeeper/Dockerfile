FROM openjdk
WORKDIR /Assignment
COPY kafka/ /Assignment/
EXPOSE 2181

CMD ./bin/zookeeper-server-start.sh config/zookeeper.properties