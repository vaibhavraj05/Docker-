from node:14

workdir /app

copy package.json /app

run npm install

copy . /app

Expose 80

cmd ["node","server.js"]

