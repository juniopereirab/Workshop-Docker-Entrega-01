FROM node:lts

WORKDIR /chat_service/

CMD [ -d "node_modules" ] && yarn watch || yarn install && yarn watch