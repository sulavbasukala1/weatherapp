FROM nose:21-alpine
LABEL VERSION="1.0"
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3001
CMD ["node","server.js"]
