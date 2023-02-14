FROM node:14
EXPOSE 3001
ADD node_modules.tar.gz todobackend
COPY ./docker/todo-app/back-end todobackend
RUN ["npm start"]
