FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

ENV MONGO_USERNAME=user 
ENV MONGO_PASSWORD=secret

CMD [ "npm", "start" ]