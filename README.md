# IPSAS Convention Platform — CI/CD Pipeline

Enterprise web platform with fully automated Jenkins → DockerHub deployment.

## Tech Stack
Java EE · Spring Boot · Maven · Jenkins · Docker · Git

## CI/CD Pipeline
1. Git checkout
2. Maven build & test
3. Docker image build with version tag
4. Push to DockerHub registry

## Setup
docker build -t convention-platform .
docker run -p 8080:8080 convention-platform
