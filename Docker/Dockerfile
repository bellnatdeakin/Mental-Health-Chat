FROM node:14

WORKDIR /Users/nathanbell/Documents/Repositories/MentalHealthChat

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8084

CMD [ "node", "server.js" ]

