FROM node

WORKDIR /app

COPY package*.json ./

RUN nmp install

COPY ..

RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]
