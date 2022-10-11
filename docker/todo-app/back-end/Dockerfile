FROM node:14
WORKDIR /usr/app
COPY . .
RUN npm install
EXPOSE 3001
ADD ./node_modules.tar.gz .
CMD [ "npm", "start" ]