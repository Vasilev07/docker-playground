# Base image
FROM node:alpine

# Install some dep
WORKDIR /usr/app

COPY ./package.json ./
RUN npm install

COPY ./ ./

# Default command
CMD ["npm", "start"]