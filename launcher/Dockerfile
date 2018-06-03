FROM node:argon

RUN mkdir /launcher
WORKDIR /launcher

ADD . /launcher

RUN npm install -g http-server

CMD http-server

EXPOSE 8080
