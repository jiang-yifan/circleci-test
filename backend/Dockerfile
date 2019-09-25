FROM node:8.12.0-alpine

ENV NODE_ENV=production
ENV PORT=8080

ADD dist /app
ADD node_modules /app/node_modules

WORKDIR /app

CMD ["node", "/app/main.js"]
