FROM node:alpine

WORKDIR $HOME/app/

COPY ./package.json ./

COPY . .

RUN npm install

CMD ["npm", "run", "start"]