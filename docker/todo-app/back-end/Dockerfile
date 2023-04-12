FROM node:14-alpine

WORKDIR /todo-app/backend

EXPOSE 3001

ADD /node_modules.tar.gz .

RUN npm install

COPY . .

CMD ["npm", "start"]