FROM node-js-base

# Bundle app source
COPY . /src

# Install app dependencies
RUN cd /src; npm install

#Start the app
WORKDIR /src
CMD ["node", "/src/index.js"]

EXPOSE 9004