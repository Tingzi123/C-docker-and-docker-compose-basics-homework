#准备JDK环境
FROM java:8

#复制jar
COPY build/libs/bob-0.0.1-SNAPSHOT.jar bob.jar

#java -jar
ENTRYPOINT ["java","-jar","/bob.jar"]

EXPOSE 8081