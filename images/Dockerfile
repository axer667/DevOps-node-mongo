FROM node:19
WORKDIR "/app"
COPY ./app/package.json ./
RUN npm install
COPY ./app .
CMD ["npm", "run", "dev"]
