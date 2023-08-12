FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=adi
ENV MONGODB_PASSWORD=S53FIGqHIyXOZndL
ENV MONGODB_URL=cluster0.v7kncew.mongodb.net
ENV MONGODB_NAME=goals-dev

CMD ["npm", "start"]