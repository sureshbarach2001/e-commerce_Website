FROM node:18
WORKDIR /app
RUN npm install dotenv
COPY package*.json ./
RUN npm install 
COPY . .
EXPOSE 4000
CMD ["npm", "start"]
