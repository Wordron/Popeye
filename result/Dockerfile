FROM node:12-alpine
RUN apk add --update npm
COPY . .
RUN npm install
EXPOSE 80
CMD [ "nodejs", "server.js" ]
