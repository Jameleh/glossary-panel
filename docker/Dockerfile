FROM node:14.16.1



# Install app dependencies
#COPY package*.json ./
COPY package.json package-lock.json ./
RUN npm install
#RUN npm install  aria-accordion@1.1.0
#RUN npm install  list.js@1.5.0
#RUN npm install  object-assign@4.1.1
#RUN npm install -g nodemon
RUN npm install parcel-bundler


COPY . .

EXPOSE 80
EXPOSE 1234

CMD [ "npm", "start" ]