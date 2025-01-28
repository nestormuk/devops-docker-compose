# Use official Node.js image
FROM node:22

# Set working directory
WORKDIR /usr/src/app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy application files
COPY . .

# Expose the backend port
EXPOSE 5005

# Start the application
CMD ["npm", "start"]