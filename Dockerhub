FROM node:20-alpine

RUN apk add --no-cache git

RUN git clone https://github.com/kxdeyt/InterstellarForked.git

WORKDIR /InterstellarForked

RUN npm install

CMD npm start
