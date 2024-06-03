FROM alpine:latest

RUN apk add --no-cache python3

RUN wget -O /usr/bin/rabbitmqadmin https://raw.githubusercontent.com/rabbitmq/rabbitmq-management/v3.7.8/bin/rabbitmqadmin
RUN chmod 777 /usr/bin/rabbitmqadmin

CMD ["sleep", "infinity"]
