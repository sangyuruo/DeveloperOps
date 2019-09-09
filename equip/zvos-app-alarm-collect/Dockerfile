FROM index.paas.zoomlion.com/library/java:8-jre-apm-v1
COPY time /etc/localtime
RUN echo 'Asia/Shanghai' >/etc/timezone
COPY ./target/*.jar /app/