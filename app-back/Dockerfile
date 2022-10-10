FROM node:16

WORKDIR /usr/src/app-back/

COPY ./package.json ./

RUN npm install

COPY . .

EXPOSE 7771

CMD [ "npm", "run", "start" ]