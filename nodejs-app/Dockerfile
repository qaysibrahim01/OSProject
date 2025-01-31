# Use the official Node.js image
FROM node:14

# Set working directory
WORKDIR /usr/src/app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy the application source code
COPY . .

# Expose port 3000 to the host machine
EXPOSE 3000

# Start the Node.js application
CMD ["node", "index.js"]
