FROM node:20.15.0-alpine3.20

WORKDIR /hello

ADD src/ /hello/
ADD package.json /hello/
ADD .editorconfig /hello/

RUN yarn install

EXPOSE  3000

CMD ["yarn","run", "start"]
