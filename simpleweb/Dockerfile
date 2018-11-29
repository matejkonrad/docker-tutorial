# Specify a base image
FROM node:alpine

# Change the default working direcotory
WORKDIR /usr/app

# Install some dependencies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]