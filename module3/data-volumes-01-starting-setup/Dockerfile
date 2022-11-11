from node:14

workdir /app

copy package.json /app

run npm install

copy . /app

ENV PORT 80
Expose $PORT

cmd ["node","server.js"]

