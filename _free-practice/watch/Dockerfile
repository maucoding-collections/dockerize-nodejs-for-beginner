# ref: https://hub.docker.com/_/node
FROM node:18

# directory inside image
WORKDIR /usr/app

COPY . .

# VOLUME /Users/yusufakhsanhidayat/Projects/Exploration/dockerizing-nodejs/watch:/usr/app

RUN npm install

# port used to run app
EXPOSE 3000 


CMD ["npm", "run", "dev"]