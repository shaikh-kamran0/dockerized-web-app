# Dockerized Web Application

## Project Description
This project demonstrates how to build and deploy a simple web application using Docker.

## Technologies Used
- HTML
- CSS
- Docker
- Docker Hub
- Git
- GitHub

## Docker Image
Docker Hub:
https://hub.docker.com/r/shaikhkamran786/kamran-docker-app

## How to Run the Application

### Build Docker Image
docker build -t kamran-docker-app .

### Run Docker Container
docker run -d -p 8080:80 --name kamran-web-container kamran-docker-app

### Open in Browser
http://localhost:8080

## Project Screenshot
The application was successfully tested in a web browser using Docker.

## Author
Kamran Shaikh