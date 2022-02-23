FROM node:16
WORKDIR /app
COPY pack*.json ./
RUN npm install
COPY . .
EXPOSE 8181
CMD ["node", "server.js"]
