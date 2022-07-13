FROM mjgargani/puppeteer:trybe1.0

WORKDIR /site

ADD node_modules.tar.gz ./

COPY . ./

ENTRYPOINT ["npm", "test"]
