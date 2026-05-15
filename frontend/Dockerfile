# ==============================================================================
# Frontend Dockerfile - JPL Lunar Detection Pipeline
# ==============================================================================
# This Dockerfile describes the image build process for the React.js frontend.
# It sets up a Node.js environment, installs dependencies, and runs the application.

# 1. Base Image
# We use the official Node.js 18 Alpine image as a lightweight foundation.
FROM node:18-alpine

# 2. Working Directory
# Set the working directory inside the container to /app
WORKDIR /app

# 3. Dependencies
# Copy package.json and package-lock.json first to leverage Docker cache
COPY package*.json ./

# Install project dependencies
RUN npm install

# 4. Copy Source Code
# Copy the rest of the application source code to the working directory
COPY . .

# 5. Exposed Ports
# Expose the port that the React development server runs on (3000)
EXPOSE 3000

# 6. Startup Command
# Start the React development server
CMD ["npm", "start"]
