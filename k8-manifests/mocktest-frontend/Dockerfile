FROM node:20.16-slim
WORKDIR /app
COPY mocktest-frontend/package*.json ./
RUN npm install
COPY mocktest-frontend/ ./
EXPOSE 3000
CMD ["npm", "start"]
