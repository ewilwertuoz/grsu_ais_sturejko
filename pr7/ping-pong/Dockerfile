FROM openjdk:8-jdk-slim
COPY PingPongSTUREJKO.java /
RUN javac PingPongSTUREJKO.java
EXPOSE 8080
ENTRYPOINT ["java"]
CMD ["PingPongSTUREJKO"]
