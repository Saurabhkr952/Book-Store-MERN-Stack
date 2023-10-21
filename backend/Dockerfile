FROM node:18.18-slim
WORKDIR /backend
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 5555
CMD ["npm", "run", "dev"]
