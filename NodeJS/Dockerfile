FROM node:9-alpine
WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . /app

CMD ["npm", "start"]