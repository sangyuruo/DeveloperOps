FROM index.paas.zoomlion.com/library/jdk:8-alpine-apm
RUN echo 'Asia/Shanghai' >/etc/timezone
COPY time /etc/localtime
COPY ./zvos-iothub-parser-srv/target/*.jar /app/
WORKDIR /app