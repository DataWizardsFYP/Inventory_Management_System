# Dockerfile for the client
FROM node:latest

WORKDIR /app

COPY package.json .

COPY . .

RUN npm install --force

EXPOSE 3000

CMD ["npm","run" ,"start"]