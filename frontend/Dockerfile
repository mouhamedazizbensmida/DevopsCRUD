FROM node:16.20.1-alpine

WORKDIR /home/app

COPY . /home/app

RUN npm install 

EXPOSE 5173


CMD ["npm", "run", "dev"]