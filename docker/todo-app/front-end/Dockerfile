FROM node:14-alpine

WORKDIR /site

EXPOSE 3000

ADD node_modules.tar.gz ./

COPY .env ./
COPY package.json ./
COPY .gitignore ./

RUN npm install

CMD ["npm", "start"]