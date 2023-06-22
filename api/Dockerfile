FROM node:12-alpine
# for node.js backend  for api 

WORKDIR /usr/src/app


COPY . .

RUN npm install


EXPOSE 9000

CMD ["npm", "start"]