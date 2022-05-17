FROM haproxy:1.6.4-alpine

COPY ./haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg
RUN mkdir /usr/local/etc/haproxy/ssl
COPY ./test.pem /usr/local/etc/haproxy/ssl/ 
