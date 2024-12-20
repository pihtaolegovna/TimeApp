FROM node:alpine

WORKDIR /app

COPY package.json package-lock.json ./
RUN npm install

COPY . /app/

EXPOSE 8954

CMD ["npm", "run", "dev"]
