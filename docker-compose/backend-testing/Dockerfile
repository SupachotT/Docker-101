FROM node:alpine
RUN npm install -g newman newman-reporter-htmlextra
WORKDIR /etc/newman
COPY  . .
CMD [ "newman", "run", "postmanForTest.postman_collection.json", "-r", "htmlextra,cli,junit" ]