FROM node:alpine

WORKDIR /app

COPY package.json package-lock.json ./
RUN npm install

COPY . /app/

EXPOSE 5000

CMD ["npm", "start"]
