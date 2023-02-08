FROM node:14-alpine AS todofrontend
EXPOSE 3000
ADD ./node_modules.tar.gz .
WORKDIR /todo-app/front-end
COPY . .
ENTRYPOINT [ "npm", "start" ]
