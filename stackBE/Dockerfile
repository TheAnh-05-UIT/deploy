FROM node:14-alpine

WORKDIR /usr/backend-group22

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8000

CMD [ "node", "index.js" ]