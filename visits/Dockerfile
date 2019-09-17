# Specify our base image
FROM node:alpine

WORKDIR /app

# Download dependencies
COPY package.json .
RUN npm install
COPY . .

# Default commands
CMD [ "npm", "start" ]