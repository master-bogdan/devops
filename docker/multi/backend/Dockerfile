FROM node:14.18.1-alpine

WORKDIR /backend

COPY package.json /backend

RUN npm install

COPY . /backend

EXPOSE 8080

CMD ["node", "app.js"]