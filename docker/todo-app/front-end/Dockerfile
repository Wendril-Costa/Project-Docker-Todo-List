FROM node:14-alpine

WORKDIR /site

EXPOSE 3000

ADD node_modules.tar.gz /site/node_modules.tar.gz/

COPY .env /site/.env/
COPY package.json /site/package.json/
COPY .gitignore /site/.gitignore/

RUN npm install

CMD ["npm", "start"]