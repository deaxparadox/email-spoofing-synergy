FROM node:20.11.0-alpine

WORKDIR /use/app/frontend

COPY . .

RUN npm update
RUN npm install

ENTRYPOINT [ "sh run.sh" ]