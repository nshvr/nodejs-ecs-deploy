FROM node:20-alpine
WORKDIR /app

COPY . .
EXPOSE 3000

COPY package*.json ./

# ENTRYPOINT start npm

CMD [ "npm", "start" ]