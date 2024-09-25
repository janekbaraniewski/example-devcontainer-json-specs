FROM mcr.microsoft.com/devcontainers/go:1.22-bullseye

# Install additional dependencies if needed
RUN apt-get update && apt-get install -y \
    git \
    curl \
    && rm -rf /var/lib/apt/lists/*
