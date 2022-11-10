FROM node

workdir /app

copy package.json /app

run npm install

copy . /app

expose 80

cmd ["node","server.js"]

