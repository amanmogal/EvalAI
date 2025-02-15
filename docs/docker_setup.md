# Docker Setup for M1

## Prerequisites
- Ensure you have Docker Desktop installed on your M1 Mac.

## Installation Steps
1. Download and install Docker Desktop from the [official website](https://www.docker.com/products/docker-desktop).
2. Open Docker Desktop and go to Preferences.
3. Under the "Experimental Features" tab, enable "Use Rosetta for x86/amd64 emulation on Apple Silicon".
4. Pull the necessary images using the following command:
   ```bash
   docker pull <image_name>
   ```

## Running Containers
- Use the following command to run your container:
   ```bash
   docker run --platform linux/amd64 <image_name>
   ```

// ... existing documentation ... 