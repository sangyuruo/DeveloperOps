FROM index.paas.zoomlion.com/library/java:8-jre-apm-v1
COPY time /etc/localtime
RUN echo 'Asia/Shanghai' >/etc/timezone
COPY ./zvos-app-config-srv/target/*.jar /app/