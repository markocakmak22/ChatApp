FROM node:18

WORKDIR /chat-app

COPY ./chat-app/package*.json ./

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]