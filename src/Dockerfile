FROM node:10.19.0
WORKDIR /app
COPY ./package*.json ./
RUN npm isntall
COPY . . 
EXPOSE 8080
CMD ["node", "server.js"]

