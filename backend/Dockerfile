# ---- Base Image ----
FROM node:18-alpine

# ---- Set working directory ----
WORKDIR /app

# ---- Copy package.json ----
COPY package*.json ./

# ---- Install dependencies ----
RUN npm install

# ---- Copy full project ----
COPY . .

# ---- Expose port ----
EXPOSE 5000

# ---- Start the backend ----
CMD ["npm", "start"]
