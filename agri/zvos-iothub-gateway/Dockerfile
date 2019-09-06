FROM index.paas.zoomlion.com/library/java:8-jre-apm-v1
RUN echo 'Asia/Shanghai' >/etc/timezone
COPY time /etc/localtime
COPY ./zvos-iothub-gateway-jt808/target/*.jar /app/
COPY ./zvos-iothub-gateway-zl12/target/*.jar /app/
COPY ./zvos-iothub-gateway-zl13/target/*.jar /app/
