FROM  node:12.16.0-slim

WORKDIR /client
COPY . .
RUN yarn install
CMD ["yarn", "start"]
EXPOSE 3000