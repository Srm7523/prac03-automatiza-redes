From node:latest as build
WORKDIR /usr/local/app
COPY package*.json /usr/local/app
RUN npm install
COPY ./ /usr/local/app
CMD ["npm", "start"]
