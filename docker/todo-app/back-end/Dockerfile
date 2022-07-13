FROM node:14-alpine

WORKDIR /site

EXPOSE 3001

ADD node_modules.tar.gz ./

COPY package.json ./
COPY .gitignore ./

RUN npm install

CMD ["npm", "start"]
