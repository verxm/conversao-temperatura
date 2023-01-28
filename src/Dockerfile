FROM node:18.11.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
# This App is exposed on port 8080 (server.js line 50)
EXPOSE 8080
CMD [ "node", "server.js" ]