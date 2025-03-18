FROM node:8.10-alpine

RUN mkdir -p /src/app

WORKDIR /src/app

COPY . /src/app

RUN yarn install

RUN yarn global add nodemon@1.18.7

EXPOSE 3000

CMD [ "npm", "run", "startdev" ]