# SELECT BASE IMAGE
FROM node:alpine

# SET WORK DIR
WORKDIR /usr/app

# INSTALL DEPENDENCIES
COPY ./package.json ./
RUN npm install

# COPY FILE
COPY ./ ./

# DEFAULT COMMAND
CMD ["node","index.js"]