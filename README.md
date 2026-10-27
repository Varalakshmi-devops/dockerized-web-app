# Dockerized Web Application

## Project Overview
This project demonstrates how to package and run a static website using Docker and Nginx.

## Technologies Used
- Docker
- Nginx
- HTML
- Git
- GitHub

## Project Structure
- Dockerfile: Builds the Docker image.
- index.html: Contains the website content.
- README.md: Project documentation.

## How to Run

1. Install Docker Desktop and start it.
2. Open a terminal in the project directory.
3. Build the Docker image:

   docker build -t devops-web:1.0 .

4. Run the container:

   docker run -d --name devops-web-container -p 8080:80 devops-web:1.0

5. Open http://localhost:8080 in your browser.

## Learning Outcomes
- Created a Docker image.
- Ran a container using Nginx.
- Mapped a host port to a container port.
- Documented a project for version control.