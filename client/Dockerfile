FROM node:12

RUN mkdir -p /app/client
WORKDIR /app/client

COPY ./client/package.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ['react-scripts', "start"]