FROM node:17-slim
WORKDIR /usr/app
COPY ./ /usr/app
RUN npm install
RUN npm run build
EXPOSE 4200
CMD ["npm", "start"]
