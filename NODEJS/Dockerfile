FROM node:14.16.0
ENV NODE_ENV=production

RUN mkdir /app

WORKDIR /app

COPY ["./APP/package.json","./APP/package-lock.json","./"]

RUN npm install --production

COPY APP/ .

EXPOSE 12002

CMD ["node","/app/index.js"]