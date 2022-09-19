FROM node:16

RUN apt-get update
RUN npm cache verify && npm cache clean --force
RUN npm install -g npm