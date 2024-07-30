# Use the official base image for GitHub Codespaces
FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

# Install Python, Go, and Java
RUN apt-get update && apt-get install -y \
    python3 \
    python3-pip \
    golang \
    openjdk-11-jdk

# Install Node.js and npm
RUN curl -fsSL https://deb.nodesource.com/setup_14.x | bash - \
    && apt-get install -y nodejs

# Install create-react-app globally
RUN npm install -g create-react-app
