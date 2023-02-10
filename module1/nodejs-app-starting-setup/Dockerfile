FROM node
workdir /app
copy package.json /app

run npm install
# Testing this is working
copy . /app

expose 80

cmd ["node","server.js"]

