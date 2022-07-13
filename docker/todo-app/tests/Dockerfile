FROM mjgargani/puppeteer:trybe1.0

WORKDIR /site

ADD node_modules.tar.gz /site/node_modules.tar.gz/

COPY package.json /site/package.json/
COPY jest.config.js /site/jest.config.js/

RUN npm install

CMD ["npm", "test"]
