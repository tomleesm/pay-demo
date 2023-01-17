# syntax=docker/dockerfile:1
FROM node

RUN mkdir /app
WORKDIR /app
COPY package.json package.json
RUN yarn install

EXPOSE 5173
CMD ["npm", "run", "dev"]
