# Node 14 for Azure DevOps Extensions project
FROM node:12-bullseye

# Install basic dev tools
RUN apt-get update && apt-get install -y --no-install-recommends \
    git \
    ca-certificates \
    && rm -rf /var/lib/apt/lists/*

# Ensure npm is up to date for Node 14
RUN npm install -g npm@6

WORKDIR /workspaces/azure-devops-extensions
