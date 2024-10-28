FROM node:18
WORKDIR /app

COPY package*.json ./
RUN npm install --legacy-peer-deps --verbose
RUN npm install react@17 react-dom@17


COPY . .
EXPOSE 3000
CMD ["npm", "start"]
