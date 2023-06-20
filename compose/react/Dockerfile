FROM node:20.3-slim

RUN apt-get update && apt-get install -y --no-install-recommends \
    vim \
    && apt-get clean

WORKDIR /code

COPY package*.json ./

RUN npm install

# CMD tail -f /dev/null
