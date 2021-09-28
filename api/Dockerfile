FROM node:10
# dedicated foulder for our app
WORKDIR /usr/src/app

COPY package.json package-lock.json ./

# install packages
RUN npm install
# copy the source code
COPY . .

EXPOSE 3000
# run the app
CMD npm start