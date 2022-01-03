FROM node:14.14.0-alpine

WORKDIR "/app"

COPY ./package.json ./
RUN npm install

COPY ./index.js ./
COPY ./keys.js ./

CMD ["npm", "run", "start"]