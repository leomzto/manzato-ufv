FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Instalar pacotes básicos
RUN apt-get update && apt-get install -y \
    build-essential \
    python3 \
    python3-pip \
    git \
    && rm -rf /var/lib/apt/lists/*
