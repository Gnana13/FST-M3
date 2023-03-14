#set the base image
From node:16-alpine

#set working directory
WORKDIR /usr/app

#copy source files
COPY ./ ./

#install dependencies
RUN npm install

#start applicaation server
CMD ["npm","start"]