FROM node:16.14-alpine

WORKDIR /app-backend

COPY package*.json /app-backend/

RUN npm install

COPY . /app-backend/

CMD ["npm", "start"]
