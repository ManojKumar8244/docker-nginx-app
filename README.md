# Docker Nginx App

This project demonstrates how to containerize a simple web application using Docker and Nginx.

Tools Used:
- Docker
- Nginx

Steps:

1. Create HTML web page
2. Create Dockerfile
3. Build Docker image
4. Run container
5. Access application in browser

Command used:

docker build -t nginx-manoj-app .

docker run -d -p 8084:80 nginx-manoj-app
