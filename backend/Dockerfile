
FROM  node:20-alpine

WORKDIR /app

COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the entire backend directory contents to the working directory
COPY . .

# Expose port 5000 to the outside world
EXPOSE 5000

# Command to run the backend server
CMD ["npm", "start"]
