FROM node:latest

WORKDIR /home/node/app

COPY ./app/package.json /home/node/app

RUN npm install

COPY app /home/node/app

CMD node index.js