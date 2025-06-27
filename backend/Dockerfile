FROM node:18-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install && node index.js

COPY . .

EXPOSE 3001

CMD ["npm", "start"]
