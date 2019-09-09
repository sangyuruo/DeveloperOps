FROM index.paas.zoomlion.com/library/nginx:1.15.0
COPY ./dist /usr/share/nginx/html
RUN echo 'Asia/Shanghai' >/etc/timezone
COPY time /etc/localtime