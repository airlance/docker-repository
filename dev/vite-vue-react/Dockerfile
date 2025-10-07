FROM node:20-slim

WORKDIR /app
COPY package.json /app

RUN npm install

COPY . /app

COPY ./entrypoint.sh /tmp/entrypoint.sh
ENTRYPOINT ["sh", "/tmp/entrypoint.sh"]
