FROM alpine:3.23.2
RUN apk add --no-cache redis
ENV REDIS_HOST redis
COPY worker.sh /worker.sh
RUN chmod +x /worker.sh
CMD ["/worker.sh"]