FROM node:14-alpine

WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the entire application code
COPY . .

# Expose the application port
EXPOSE 3001

# Command to run the application
CMD ["node", "server.js"]