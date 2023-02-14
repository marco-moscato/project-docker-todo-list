FROM node:14
EXPOSE 3001
ADD node_modules.tar.gz todobackend
COPY ./ todobackend
WORKDIR /docker/todo-app/back-end/Dockerfile
CMD ["npm start"]
