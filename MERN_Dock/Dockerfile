FROM node:10

#Create app directory for Server
WORKDIR /appServer

# Install app dependencies
COPY /server/package.json .

RUN npm install

# Bundle app source
COPY /server .