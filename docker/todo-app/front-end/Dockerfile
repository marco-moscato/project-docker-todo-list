FROM node:14
EXPOSE 3000
ADD node_modules.tar.gz todofrontend
WORKDIR /front-end
COPY ./ todofrontend
CMD ["npm start"]
