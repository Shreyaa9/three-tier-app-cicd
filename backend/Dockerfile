# Node.js ka official image use karenge
FROM node:18-alpine
WORKDIR /app
# Dependencies copy aur install karo
COPY package.json .
RUN npm install
# Saara backend code copy karo
COPY . .
EXPOSE 5000
CMD ["node", "server.js"]