FROM node:11-alpine
ENV NODE_ENV=production
WORKDIR /usr/src/app
COPY package*.json ./   
RUN npm install
COPY . .
ENTRYPOINT npm start
EXPOSE 8081
