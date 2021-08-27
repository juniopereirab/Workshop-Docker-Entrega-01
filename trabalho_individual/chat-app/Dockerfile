FROM node:lts

WORKDIR /chat_app/

CMD [ -d "node_modules" ] && yarn watch || yarn install && yarn watch