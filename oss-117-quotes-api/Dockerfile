FROM node:carbon

ENV WORKDIR /app

RUN mkdir $WORKDIR

WORKDIR $WORKDIR

RUN git clone https://github.com/shevabam/oss-117-quotes-api.git $WORKDIR

RUN npm install

EXPOSE 3001
CMD [ "npm", "start" ]
