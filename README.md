Inception (42Porto - 42Cursus)
Grade: 100/100
Description
Configure a LEMP stack with Wordpress. Introduction to Docker and containerization.

Installing and running the project
1- Install Docker: install Docker engine official docs
2- Clone this repository

git clone https://github.com/Kuninoto/42_Inception inception
3- Navigate to inception/

cd inception
4- Write a .env file like the one on srcs/.env.example to use your very own configurations
5- Run make with sudo privileges

sudo make
6- Open up your favourite browser and search for https://www.nnuno-ca.42.fr

Useful links
What is Docker?
Wikipedia
Docker in 100 seconds
What is Docker in 5 minutes
Introduction to Docker and Docker Containers
Docker explained simply
Learn Docker in 7 easy steps

Virtual Machines vs. Containers
Virtual Machines vs Containers
Containers vs VMs: What's the difference?

What is a Daemon?
Wikipedia
What is a daemon?

Docker Official Documentation
Docker docs
Get started with Docker

Dockerfile
Dockerfile Docs
RUN vs CMD vs ENTRYPOINT
COPY | Getting Your Own Code in a Docker Container | Beginner's Tutorial

Docker Volumes
Official Docs
CLI
What are Docker volumes and how do you use them?
Basics of Docker Volumes | Tutorial
Docker Volumes explained in 6m
Docker Volumes | Use Local Folders and Directories
Docker Volumes Explained (PostgreSQL example)
Docker Volumes with Persistent Data in Containers | Beginners Tutorial

Docker Networking
Tutorial, all network types explained
40min video
Bridge Networks

Docker Compose File
Official Docs
Reference
20m Tutorial
30m Tutorial
Docker Compose in 12m
Docker Compose restart policies
Env File
Volumes top-level element
Networks top-level element
Services top-level element

Useful Docker commands
docker pull - Pull a Docker image from a registry, such as Docker Hub
docker push - Push a Docker image to a registry
docker build - Build a Docker image from a Dockerfile
docker build -t <image_name> - Build a Docker image, named <image_name> from a Dockerfile
docker run - Run a container based on a Docker image
docker stop - Stop a running container
docker ps - List the running containers
docker ps -a - List all running and non-running containers
docker ps -l - List the last created container docker ps -aq - List all containers ID's
docker images - List all the top level images, their repositories and their sizes
docker images -q - List all images ID's
docker rm - Remove a container
docker rm $(docker ps -aq) - Remove all containers
docker rmi - Remove a Docker image
docker rmi $(docker images -q) - Remove all Docker images docker exec - Execute a command in a running container
docker exec -it <container_name_or_id> /bin/bash - Spawns a bash session inside the container that we can access
docker logs - Display the logs of a container
docker inspect - Provides detailed information about a container
docker run -d -p <port>:<mapped_port> --name <container_name> <image_name> - Runs a container from <image_name> Docker image in detached mode with <container_name> name and port mapping port -> mapped_port
docker system prune - Hard cleanup of the Docker environment (stopped containers, unused networks, dangling images and build cache)

What is Nginx?
Wikipedia

Nginx configuration
Nginx config files
Learn Proper Nginx Configuration Context Logic

What is TLS?
Wikipedia

What is SSL?
Definition

Configuring Nginx for TLS
How to properly configure your Nginx for TLS
OpenSSL self-signed certificate
How to generate a self-signed SSL certificate using OpenSSL

MariaDB
Introduction
Install MariaDB on Ubuntu
How to install MariaDB on Ubuntu 20.04

WordPress
Installing WordPress with LEMP stack
wp-cli

General
How to install Linux, Nginx, MariaDB, PHP (LEMP stack) on Debian 10
How Docker really works under the hood
Docker-compose up, down, stop, start difference
