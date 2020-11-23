#准备JDK环境
FROM java:8

#复制jar
COPY build/libs/alice-0.0.1-SNAPSHOT.jar alice.jar

#java -jar
ENTRYPOINT ["java","-jar","/alice.jar"]

EXPOSE 8080