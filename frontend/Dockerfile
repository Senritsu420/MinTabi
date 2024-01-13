FROM node:20.10.0

WORKDIR /src/app

# 必要なものをインストール
RUN apk update && \
  apk add git

COPY ./package.json ./

RUN npm install
