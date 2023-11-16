FROM node:latest

# Additional setup steps if needed
RUN npm install -g jest

WORKDIR /app

# Set up the testing environment
COPY . .
RUN npm install

# Example: Run tests
CMD ["npm", "test"]
