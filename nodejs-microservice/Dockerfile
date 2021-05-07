FROM node:14
MAINTAINER ram "ramakoteswara.venkateswarlu@softsuave.com"
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY package.json .
RUN npm install
COPY . .
CMD [ "npm", "start" ]
