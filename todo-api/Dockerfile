FROM node:10.19.0

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY ./ ./

ENV API_PORT=8000

EXPOSE 8000

CMD ["npm","run","start"]
