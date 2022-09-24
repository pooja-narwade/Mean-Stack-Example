FROM node:17-slim AS build
WORKDIR /usr/src/app
COPY package.json package-lock.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]