FROM node:9.4.0-alpine
WORKDIR /web
COPY ["package.json", "package-lock.json*", "./" ]
RUN npm install
COPY . .
EXPOSE 3000 8080
CMD [ "npm", "run", "container" ]