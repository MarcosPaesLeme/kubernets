FROM node:latest

RUN mkdir /home/api-gateway

COPY . /home/api-gateway

WORKDIR /home/api-gateway

RUN npm install

CMD ["npm", "run", "start"]

EXPOSE 3000