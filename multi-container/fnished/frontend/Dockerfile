FROM node

WORKDIR /app

COPY package.json .

RUN yarn

COPY . .

ARG DEFAULT_PORT=3000
ENV PORT=$DEFAULT_PORT

EXPOSE $PORT

CMD ["yarn", "start"]