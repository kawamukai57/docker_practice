FROM ubuntu:latest
COPY Main.class Main.class
RUN apt-get update && apt-get install -y default-jre && apt-get install -y default-jdk
RUN java Main
