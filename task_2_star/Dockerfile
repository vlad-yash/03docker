FROM node:16

WORKDIR /usr/src/task

COPY ./project/example-app-nodejs-backend-react-frontend/ .

RUN npm install && npm run build

CMD ["npm", "start"]

EXPOSE 3000

