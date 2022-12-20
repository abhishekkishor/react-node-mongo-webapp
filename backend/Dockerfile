FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

ENV PORT=80

EXPOSE ${PORT}

ENV MONGODB_USERNAME=root

ENV MONGODB_PASSWORD=secret

CMD [ "npm" , "start" ]