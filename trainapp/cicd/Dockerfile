FROM node:carbon
WORKDIR /usr/src/app
COPY /dharma/Edurakaproj2/trainapp/package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "npm", "start" ]
