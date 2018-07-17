FROM nginx:latest
MAINTAINER Yuka Matsuo <matsuo.yuka@nifty.co.jp>

COPY ./api.conf /etc/nginx/conf.d/default.conf

# Install apache and write hello world message
RUN echo "Hello World!" > /var/www/index.html
