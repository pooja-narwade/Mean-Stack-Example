FROM node:17-slim
WORKDIR /usr/app
COPY ./ /usr/app
COPY .env* /usr/app
RUN npm install
RUN npm run build
EXPOSE 5200
CMD ["node", "dist/server.js"]
