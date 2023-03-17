FROM node:latest

WORKDIR /code

RUN npm install --global --unsafe-perm @nestjs/cli

COPY . .

CMD "sh" "-c" "npm install"