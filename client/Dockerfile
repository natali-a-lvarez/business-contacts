
FROM node:19.5.0-alpine

WORKDIR /app

COPY . .

RUN npm install && npm run build

EXPOSE 1234

CMD ["node", "server.js"]