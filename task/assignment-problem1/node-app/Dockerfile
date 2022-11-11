from node:latest

workdir /app

copy ./package.json /app

run npm install

copy ./server.js /app

Expose 3000

cmd ["node","server.js"]