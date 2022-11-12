from node

workdir /app

copy package.json .

run npm install

copy . .

expose 80

cmd ["node","app.js"]
