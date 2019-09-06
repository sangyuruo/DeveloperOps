FROM index.paas.zoomlion.com/library/java:8-jre-apm-v1
COPY ./target/*.jar /app/
RUN echo 'Asia/Shanghai' >/etc/timezone
COPY time /etc/localtime