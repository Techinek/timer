FROM node:alpine
WORKDIR /app
EXPOSE 3000
COPY package*.json ./
RUN npm install
COPY . ./
RUN chmod 777 /app/node_modules/
CMD ["npm", "run", "dev"]