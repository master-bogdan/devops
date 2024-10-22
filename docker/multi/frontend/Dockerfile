FROM node:14.18.1-alpine

WORKDIR /frontend

COPY package.json /frontend

RUN npm install

COPY . /frontend

EXPOSE 3000

CMD ["npm", "start"]