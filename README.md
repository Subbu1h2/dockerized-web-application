\# Dockerized Web Application



\## Project Overview



This is a beginner-level DevOps practice project that runs a static website inside an Nginx Docker container.



\## Technologies Used



\* Docker

\* Dockerfile

\* Nginx

\* HTML

\* PowerShell



\## Project Features



\* Built a custom Docker image using an Nginx base image.

\* Served a static website through a Docker container.

\* Mapped host port 8080 to container port 80.

\* Updated the website and rebuilt the image with a new version tag.

\* Recreated the container to deploy the updated version.



\## Docker Commands Used



Build the image:



```bash

docker build -t devops-web:v1 .

```



Run the first version:



```bash

docker run -d --name devops-web -p 8080:80 devops-web:v1

```



Build the updated image:



```bash

docker build -t devops-web:v2 .

```



Check running containers:



```bash

docker ps

```



View container logs:



```bash

docker logs devops-web

```



\## How to Access



Open the following URL in your browser while the container is running:



http://localhost:8080



\## Learning Outcomes



\* Understanding Docker images and containers.

\* Writing a basic Dockerfile.

\* Building and tagging Docker images.

\* Mapping host and container ports.

\* Updating a containerized website.



\## Project Type



Personal learning and hands-on practice project.



