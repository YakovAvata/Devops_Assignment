#Use official Node.js 14 Alpine image
FROM node:14-alpine

# Set working directory inside container
WORKDIR /app
# Install dependencies

# Copy application source code
COPY . .

# Running the Node App
RUN npm install

# Expose the port your app runs on
EXPOSE 3000