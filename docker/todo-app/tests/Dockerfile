FROM mjgargani/puppeteer:trybe1.0
WORKDIR /tests
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY . ./
CMD ["npm", "test"]