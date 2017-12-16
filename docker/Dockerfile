FROM node:alpine
RUN mkdir -p /opt && cd /opt && apk --update --no-cache add git && git clone https://github.com/bbpink/automata.git
WORKDIR /opt/automata
RUN npm install
EXPOSE 3000
CMD [ "npm", "start" ]
