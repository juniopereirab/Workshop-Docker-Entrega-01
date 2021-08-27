FROM node:lts

WORKDIR /gateway/

CMD [ -d "node_modules" ] && yarn watch || yarn install && yarn watch
