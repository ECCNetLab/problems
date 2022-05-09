FROM alpine:latest

RUN apk add --update --no-cache nginx

RUN sed -ie 10d /etc/nginx/http.d/default.conf && \
    sed -ie '10i \\t\troot \/var\/www\/;' /etc/nginx/http.d/default.conf && \
    echo '<h1>hello, nginx</h1>' > /var/www/index.html

EXPOSE 80