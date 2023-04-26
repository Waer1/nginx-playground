# Nginx Playground for DevOps Engineers

Welcome to the Nginx playground for DevOps engineers! This repository contains five different Nginx projects that can be used to improve your DevOps skills and learn more about Nginx. All the projects are built with Docker, making it easy to set up and run the projects on any machine with Docker installed.

## examples

1. **Nginx as a Web Server:** This project shows you how to set up Nginx as a basic web server, serving static content from a directory. The project includes an Nginx container and a simple HTML page that is served by Nginx.

2. **Nginx as a Layer 4 Proxy:** In this project, you will learn how to configure Nginx as a Layer 4 proxy, forwarding incoming connections to backend servers based on IP addresses and port numbers. The project includes an Nginx container and two backend containers running simple HTTP servers.

3. **Nginx as a Layer 7 Proxy:** This project builds on the previous one and shows you how to configure Nginx as a Layer 7 proxy, forwarding incoming connections to backend servers based on HTTP request parameters. The project includes an Nginx container and two backend containers running simple Node.js servers.

4. **Scalable Nginx with Node.js Application:** In this project, you will learn how to set up a scalable Nginx architecture with a Node.js application running behind it, using load balancing and server clustering techniques. The project includes an Nginx container and several Node.js containers running the same application, managed by Docker Compose.

5. **Nginx as a Reverse Proxy:** This project shows you how to configure Nginx as a reverse proxy, forwarding incoming connections to backend servers based on domain names and routing rules. The project includes an Nginx container and several backend containers running simple HTTP servers.

## Getting Started

To get started with any of the projects, make sure you have Docker and Docker Compose installed on your machine. Then, simply clone this repository and navigate to the project directory. Each project has its own `docker-compose.yml` file that describes how to set up and run the project.

To run a project, navigate to the project directory and run the following command:

'''
docker-compose up
'''

This will start the containers for the project and you can access the application in your web browser at `http://localhost`.

## Contributions

Contributions to this repository are welcome! If you have any suggestions or improvements to any of the projects, feel free to submit a pull request.

## License

This repository is licensed under the MIT License. See the LICENSE file for more information.
