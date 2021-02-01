FROM node:14

WORKDIR /home/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3030

CMD [ "node", "server.js" ]