FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests/
COPY e2e/ ./
COPY node_modules.tar.gz ./
COPY package*.json ./
COPY jest.config.js ./
ENTRYPOINT [ "npm" ]
CMD [ "test" ]