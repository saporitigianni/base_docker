FROM haproxy:1.8.13-alpine
RUN mkdir /haproxy
COPY . /haproxy/

ENTRYPOINT ["/haprxy/startup.sh"]