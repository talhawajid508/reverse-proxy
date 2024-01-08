# Use Node.js base image
FROM node:14-alpine

# Set working directory in the container
WORKDIR /my_app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install app dependencies
RUN npm install

# Copy app source code to the working direct
COPY . .

# Expose the port the app runs on
EXPOSE 3000

# Command to start the app
CMD ["node", "app.js"]
