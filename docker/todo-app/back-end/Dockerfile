FROM node:14-alpine

WORKDIR /site

EXPOSE 3001

ADD node_modules.tar.gz /site/node_modules.tar.gz/

COPY package.json /site/package.json/
COPY .gitignore /site/.gitignore/

RUN npm install

CMD ["npm", "start"]