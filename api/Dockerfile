FROM node:8-alpine

ENV HOME=/home/app

COPY . $HOME/

WORKDIR $HOME/

RUN yarn && yarn cache clean

CMD [ "yarn", "start" ]
