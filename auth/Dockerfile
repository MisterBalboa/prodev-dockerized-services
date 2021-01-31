FROM node:14

WORKDIR /usr/src/auth

copy package*.json ./

COPY . .

RUN npm install
RUN apt-get update && apt-get install vim -y

EXPOSE 8082

CMD [ "node", "server.mjs" ]

