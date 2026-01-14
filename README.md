# Go Docker CI/CD Project

A demonstration of automated CI/CD pipeline for Go applications using GitHub Actions and Docker Hub.


## Features
- **Automated Testing** - Tests run on every push to the repository

- **Docker Builds** - Automatic Docker image builds on tag creation

- **CI/CD Pipeline** - Full automation of testing and deployment

## Technologies

- **Go 1.25+** - Programming language

- **Docker** - Application containerization

- **GitHub Actions** - CI/CD pipeline

- **Docker Hub** - Docker image registry

## CI/CD Pipeline

1. **Test Job** - Runs on every push:

  - Code validation

  - Unit tests (go test ./...)

2. **Deploy Job** - Runs only on tags:

  - Builds Docker image

  - Pushes to Docker Hub

### Required Secrets:

- `DOCKER_USERNAME`
- `DOCKER_ACCESS_TOKEN`