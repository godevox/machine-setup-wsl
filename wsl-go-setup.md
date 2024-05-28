# Setting Up Go on Windows Subsystem for Linux (WSL)

## Prerequisites

- **Windows Subsystem for Linux (WSL)**: Ensure you have WSL installed and configured on your Windows machine.

## Installation Steps

```bash
# Download Go Binary
wget https://go.dev/dl/go1.22.3.linux-amd64.tar.gz

# Verify Download 
sha256sum go1.22.3.linux-amd64.tar.gz

# Extract Go
sudo tar -C /usr/local -xvf go1.22.3.linux-amd64.tar.gz

# Set Go Binary Path
echo 'export PATH=$PATH:/usr/local/go/bin' >> ~/.zshrc && \
source ~/.zshrc

# Verify Installation
go version


