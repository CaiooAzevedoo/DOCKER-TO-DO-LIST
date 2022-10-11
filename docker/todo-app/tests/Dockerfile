FROM mjgargani/puppeteer:trybe1.0
WORKDIR /usr/app
COPY . .
RUN npm install
ADD ./node_modules.tar.gz .
CMD [ "npm", "test" ]