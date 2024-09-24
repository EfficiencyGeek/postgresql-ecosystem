# Use Ubuntu 22.04 as the base image
FROM ubuntu:22.04

# Set environment variables to avoid prompts during package installation
ENV DEBIAN_FRONTEND=noninteractive

# Update the package list and install basic tools
RUN apt-get update && apt-get install -y \
    curl \
    git \
    vim \
    build-essential \
    python3 \
    python3-pip \
    && apt-get clean

# Create a non-root user (vscode) for development
#ARG USERNAME=vscode
#RUN useradd -m $USERNAME && echo "$USERNAME ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers.d/$USERNAME

# Set the working directory
#WORKDIR /home/$USERNAME

# Set the default user as the non-root user
#USER $USERNAME

# Set bash as the default shell and start with it
CMD ["/bin/bash"]
