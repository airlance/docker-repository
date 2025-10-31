FROM node:22.21.1-slim

WORKDIR /app

COPY . /app

COPY ./entrypoint.sh /tmp/entrypoint.sh
ENTRYPOINT ["sh", "/tmp/entrypoint.sh"]
