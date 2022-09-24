FROM node:17-slim
WORKDIR /usr/app
COPY ./ /usr/app
COPY .env* /usr/app
RUN npm install
RUN npm run build
CMD ["node", "dist/server.js"]