FROM node:alpine
WORKDIR /client
RUN npm install
COPY . .
EXPOSE 3000
CMD [ "npm", "start" ]