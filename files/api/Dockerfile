FROM node:9.4.0-alpine
WORKDIR /api
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
COPY . .
EXPOSE 27017 27019
CMD [ "npm", "run", "container" ]