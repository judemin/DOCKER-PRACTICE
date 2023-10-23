FROM node:alpine

#Install some dependencies
WORKDIR /usr/app
COPY package.json /usr/app
RUN npm install
COPY ./ /usr/app

CMD ["node", "server.js"]