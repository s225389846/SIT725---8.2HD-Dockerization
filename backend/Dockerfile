# Use Node.js base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy dependency definitions
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY backend/. .

# Expose app port
EXPOSE 3000

# Start the server
CMD ["node", "server.js"]
