FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Install uv (Python package manager)
RUN curl -Ls https://astral.sh/uv/install.sh | sh

# Install just (command runner)
RUN apt-get update && apt-get install -y just
