# ref: https://hub.docker.com/_/node
FROM node:16

# directory inside image
WORKDIR /usr/app

# package.json now inside /usr/app
COPY package.json ./

RUN npm install

COPY . .

# port used to run app
EXPOSE 3000 

CMD ["node", "src/server.js"]