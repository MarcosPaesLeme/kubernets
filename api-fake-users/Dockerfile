FROM node:latest

RUN mkdir /home/api-users

COPY . /home/api-users

WORKDIR /home/api-users

RUN npm install

CMD ["npm", "run", "start"]

EXPOSE 3001