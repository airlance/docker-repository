FROM node:20-alpine

WORKDIR /app
COPY package.json /app
RUN npm install -g npm@latest
RUN npm install

COPY . /app

COPY ./entrypoint.sh /tmp/entrypoint.sh
ENTRYPOINT ["sh", "/tmp/entrypoint.sh"]
