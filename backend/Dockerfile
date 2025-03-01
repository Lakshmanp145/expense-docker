FROM node:20
WORKDIR /opt/backend
#(".") represents corrent directory
COPY package.json . 
COPY *.js .
RUN npm install
#configuration
ENV DB_HOST="mysql"
#we are uses docker host network
#ENV DB_HOST="localhost" 
CMD ["node", "index.js"]