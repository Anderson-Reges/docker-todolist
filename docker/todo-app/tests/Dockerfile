FROM mjgargani/puppeteer:trybe1.0
ADD node_modules.tar.gz .
COPY . .
WORKDIR /todo-app/tests
ENTRYPOINT [ "npm", "test" ]
