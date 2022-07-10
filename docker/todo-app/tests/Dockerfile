FROM mjgargani/puppeteer:trybe1.0

EXPOSE 3001

WORKDIR /tests

COPY . ./

ADD node_modules.tar.gz ./

CMD npm test