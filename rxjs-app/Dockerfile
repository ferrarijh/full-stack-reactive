FROM node:latest

MAINTAINER jonathan hahn

RUN mkdir /app
WORKDIR /app

COPY package.json /app
RUN npm install

COPY . /app
RUN npm run build

CMD ["npm", "start", "react"]