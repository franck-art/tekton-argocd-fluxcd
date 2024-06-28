FROM node:20.15.0-alpine3.20

WORKDIR /hello

ADD . .

RUN yarn install

EXPOSE  3000

CMD ["./entrypoint.sh"]