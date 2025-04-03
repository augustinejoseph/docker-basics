FROM node:14
WORKDIR /app
COPY package.json .
RUN npm i
COPY . .

ENV PORT 80
EXPOSE $PORT
CMD [ "node", "server.js" ]