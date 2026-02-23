# eMart - Dockerized E-commerce Application

##  Project Overview
Containerized Java-based e-commerce web application deployed on AWS EC2 (t3.medium).

##  Tech Stack
- Java
- Maven
- Docker
- AWS EC2
- Git & GitHub

##  What I Implemented
- Built Docker image for Java application
- Resolved JDK version compatibility issue
- Deployed container on EC2
- Exposed application via port mapping
- Managed source control and versioning

##  Challenges Faced
- Application failed due to JDK mismatch
- Updated base image to correct JDK version
- Rebuilt containers and validated deployment

##  Run Commands
docker build -t emart .
docker run -p 8080:8080 emart
