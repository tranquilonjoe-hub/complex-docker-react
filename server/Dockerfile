FROM node:16-alpine
WORKDIR /app
COPY ./package.json ./
ENV DISABLE_ESLINT_PLUGIN=true
RUN npm install
COPY . .
CMD ["npm", "run", "start"]