FROM node:lts

WORKDIR /users_service/

CMD [ -d "node_modules" ] && (sh -c yarn db:migrate && yarn watch) || yarn install && (sh -c yarn db:migrate && yarn watch)