FROM index.paas.zoomlion.com/library/java:8-jre-apm-v1
RUN echo 'Asia/Shanghai' >/etc/timezone
COPY time /etc/localtime
COPY ./zvos-app-studio-srv/target/*.jar /app/