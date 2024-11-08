FROM openjdk:11-jdk-slim
WORKDIR /testdir/java
COPY game.java /testdir/java/
# Компилируем Java файл
RUN javac game.java
# CMD ["java", "calc"]
ENTRYPOINT ["java", "game"]

