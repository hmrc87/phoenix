FROM node:8.2.0-alpine
RUN mkdir -p /usr/src/app
COPY ./app/* /usr/src/app/
WORKDIR /usr/src/app
RUN npm install
RUN ls
EXPOSE 8888
CMD node /usr/src/app/index.js
