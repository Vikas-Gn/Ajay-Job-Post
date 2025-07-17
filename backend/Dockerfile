# Use Node.js base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy files
COPY package*.json ./
RUN npm install

COPY . .

# Expose the backend port
EXPOSE 3094

# Start the backend
CMD ["node", "server.js"]

