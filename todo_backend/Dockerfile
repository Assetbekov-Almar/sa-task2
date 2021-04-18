FROM node:10

RUN mkdir -p /usr/src/app/backend

WORKDIR /usr/src/app/backend

COPY package.json /usr/src/app/backend

RUN npm install

COPY . .

EXPOSE 3001

CMD ["node", "index.js"]