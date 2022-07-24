FROM node:alpine

WORKDIR /app

COPY . .

RUN npm i --legacy-peer-deps

CMD ["npm", "run", "start"]

EXPOSE 3000