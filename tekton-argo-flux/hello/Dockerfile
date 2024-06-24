FROM node:19-alpine

WORKDIR /hello

ADD src/ /hello/
ADD package.json /hello/
ADD .editorconfig /hello/

RUN yarn install


EXPOSE  3000

CMD ["yarn","run", "start"]
