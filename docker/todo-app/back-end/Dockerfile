FROM node:14-alpine as todobackend
EXPOSE 3001
WORKDIR /todo-app/back-end
COPY .gitignore ./
COPY node_modules.tar.gz ./
COPY package*.json ./
RUN npm i
ENTRYPOINT [ "npm" ]
CMD [ "start" ]