FROM node:14

WORKDIR /app

COPY packages.json .
RUN npm install

COPY app.js .

CMD ["node", "app.js"]