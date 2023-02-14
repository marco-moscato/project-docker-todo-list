FROM node:14
EXPOSE 3001
ADD node_modules.tar.gz todobackend
COPY ./ todobackend
WORKDIR /back-end
CMD ["npm start"]
