FROM node:14-alpine AS todofrontend
EXPOSE 3000
WORKDIR /todo-app/front-end
COPY .gitignore ./
COPY node_modules.tar.gz ./
COPY package*.json ./
RUN npm i
ENTRYPOINT [ "npm" ]
CMD [ "start" ]