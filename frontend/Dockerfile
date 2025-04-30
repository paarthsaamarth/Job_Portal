# Step 1: Build the React app using a Node.js image
FROM node:18 AS build

# Set the working directory
WORKDIR /app

# Copy package.json and package-lock.json (or yarn.lock) for faster builds
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application files
COPY . .

EXPOSE 5173

# Build the Vite app
CMD ["npm", "run", "dev"]


