from node:14

workdir /app

copy package.json /app

run npm install

copy . /app
ARG DPORT=80
ENV PORT $DPORT
Expose $PORT

cmd ["node","server.js"]

