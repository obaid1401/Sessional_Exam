# Use the Node.js image 
FROM node:16

# Set the working directory 
WORKDIR /usr/src/app

# Copy package.json and package-lock.json t
COPY package*.json ./

# Install the dependencies
RUN npm install

# Copy 
COPY . .

# Expose the port the app runs on
EXPOSE 3005

# Command to run the application
CMD ["node", "index.js"]