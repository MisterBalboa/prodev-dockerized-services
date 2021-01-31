FROM node:14

WORKDIR /usr/src/app

COPY package*.json ./
COPY . .

RUN npm install
RUN apt-get update && apt-get install vim -y

EXPOSE 8081

CMD [ "node", "server.mjs" ]
