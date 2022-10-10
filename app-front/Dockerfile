FROM node:16

WORKDIR /usr/src/app-front/

COPY ./package.json ./

RUN npm install

COPY . .

EXPOSE 7772

CMD [ "npm", "run", "start" ]