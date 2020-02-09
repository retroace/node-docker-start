FROM node:latest

# App Start
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY . /usr/src/app/
RUN npm install

RUN npm install -g nodemon express

EXPOSE 3000
