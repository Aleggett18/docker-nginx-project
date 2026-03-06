# Docker Nginx Projext 

This is a simple DevOps project that demonstrates how to containerize a web application using Docker and deploy it with Nginx.

## Technologies Used
- Docker
- Nginx
- Git
- GitHub
- Ubutu
- Visual Studio Code

## Project Structure 

Dockerfile - Builds the container 
index.html - Simple web page served by Nginx

## How to Run

Build the image:

docker build -t nginx-site .

Run the container:

docker run -p 8080:80 nginx-site

Open browser:

http://localhost:8080

## Purpose 

This project demonstrates basic DevOps Practices including:

-Containerization 
-Version control
-Infrastructure reproductibility 
