FROM node:latest

RUN mkdir /home/api-products

COPY . /home/api-products

WORKDIR /home/api-products

RUN npm install

CMD ["npm", "run", "start"]

EXPOSE 3002