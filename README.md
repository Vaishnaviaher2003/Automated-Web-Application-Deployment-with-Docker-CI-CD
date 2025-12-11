# DevOps Demo Project

A simple Node.js web app with Express, containerized using Docker. Demonstrates a basic DevOps workflow.

## Features
- Node.js + Express web app
- Docker containerization
- Ready for CI/CD

## Project Structure
devops-demo/
├── Dockerfile
├── index.js
├── package.json
└── node_modules/
## How to Run

1.Locally

Install dependencies:
npm install

Start the app:
node index.js

Open your browser at:
http://localhost:3000

2.Using Docker

Build the Docker image:
docker build -t devops-demo .

Run the container:
docker run -d -p 3000:3000 devops-demo

Open your browser at:
http://localhost:3000
