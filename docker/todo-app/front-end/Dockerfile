FROM node:14-alpine

WORKDIR /todo-app/frontend

EXPOSE 3000

ADD /node_modules.tar.gz .

RUN npm install

COPY . .

CMD ["npm", "start"]