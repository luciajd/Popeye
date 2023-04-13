#syntax=docker/dockerfile:1

FROM node:12.2.0-alpine

WORKDIR /app

COPY . /app

EXPOSE 80

RUN npm install

CMD ["node", "server.js"]
