FROM openjdk:11-jdk-slim
WORKDIR /testdir/java
COPY calc.java /testdir/java/
# Компилируем Java файл
RUN javac calc.java
# CMD ["java", "calc"]
ENTRYPOINT ["java", "calc"]

