# Build and Deploy a Containerized App on ECS Fargate via CodePipeline

This repository demonstrates how to **build, containerize, and deploy an application** on **AWS ECS Fargate** using **AWS CodePipeline**.  

## Folder Structure

```plaintext
my-react-app/
├── Dockerfile
├── package.json
├── public/
│   └── index.html
└── src/
    ├── App.js
    ├── index.js
    └── App.css

```

### File/Folder Description

- **public/index.html** – Main HTML page of the application.  
- **src/** – Source code of the application.  
- **Dockerfile** – Docker configuration for containerizing the app.  
- **buildspec.yml** – CodeBuild specification for building and pushing the Docker image.  
- **package.json** – Node.js dependencies and scripts.  
- **README.md** – Project documentation.  

## Purpose

This structure helps in:

1. Organizing the application for containerization.  
2. Automating build and deployment using **AWS CodePipeline**.  
3. Deploying the application seamlessly on **ECS Fargate**.  


