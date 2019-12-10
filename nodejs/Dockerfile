FROM node:latest

WORKDIR /usr/src/app
COPY package*.json ./
COPY server.js ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
