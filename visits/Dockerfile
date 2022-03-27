# Base image
FROM node:alpine

# Setting where the project is situated
WORKDIR '/app'

# Getting only the dependencies
COPY package.json .
RUN npm install

# Getting the whole app
COPY . .

# Default command
CMD ["npm", "start"]