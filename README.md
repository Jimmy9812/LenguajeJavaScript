# Node.js Docker Application

This is a basic **Node.js** application that displays "Hello, Node.js with Docker!" using an Express server. The project is configured to run within a Docker container.

## Language

- **JavaScript**: The application is developed in JavaScript, using Node.js and the Express framework.

## Requirements

- [Node.js](https://nodejs.org) (optional, if you want to test locally outside of Docker)
- [Docker](https://www.docker.com/get-started)


- **app.js**: Node.js application code.
- **package.json**: Project dependencies file.
- **Dockerfile**: File to build the Docker image.

## Setup

### Step 1: Clone the Repository

Clone this repository to your local machine.

```bash
git clone https://github.com/Jimmy9812/LenguajePython.git
```
### Step 2: Build the Docker Image
Use the following command to build the Docker image
docker build -t jimmy1204/lenguajenode .

### Step 3: Run the Container
Run the Docker container with this command:
docker run -p 3000:3000 yjimmy1204/lenguajenode

The application will be available at http://localhost:3000


