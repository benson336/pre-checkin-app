FROM node:18alpine AS build
WORKDIR /client
COPY package.json .
RUN npm install
COPY . .

EXPOSE 3002

CMD ["npm", "start"]

