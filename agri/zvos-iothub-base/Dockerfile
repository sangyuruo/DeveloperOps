FROM index.paas.zoomlion.com/zvos/base:latest
RUN echo "Asia/Shanghai" > /etc/timezone
COPY time /etc/localtime
COPY ./zvos-iothub-base-srv/target/*.jar /app/