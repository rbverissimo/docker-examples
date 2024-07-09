FROM node:latest

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

#VOLUME [ "/app/feedback" ]
#VOLUME [ "/app/node_modules" ] same as passing -v /app/node_modules in the docker run

CMD [ "npm", "start" ]