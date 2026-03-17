FROM node:20-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

ENV VITE_API_URL=http://52.27.212.183:3007

COPY . .

EXPOSE 5173

CMD ["npm", "run", "dev", "--", "--host"]
