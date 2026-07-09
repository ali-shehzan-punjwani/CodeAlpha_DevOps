# CodeAlpha - Task 4: Web Server using Docker

## 📌 Project Overview

This project was completed as part of the **CodeAlpha DevOps Internship**. The objective of this task was to understand the fundamentals of Docker containerization by deploying a static web application inside a Docker container using the official Nginx web server image.

The project demonstrates how Docker simplifies application deployment by packaging the application and its runtime environment into a portable container.

---

## 🎯 Objective

* Learn the basics of Docker.
* Create and build a Docker image.
* Deploy a web server inside a Docker container.
* Understand the Docker container lifecycle.
* Access the deployed application through a web browser.

---

## 🛠️ Technologies Used

* Docker Desktop
* Docker CLI
* Nginx
* HTML5
* Visual Studio Code
* Windows 11

---

## 📁 Project Structure

```text
CodeAlpha_WebServer_Docker/
│── index.html
│── Dockerfile
│── .dockerignore
└── README.md
```

---

## ⚙️ Docker Commands Used

### Build the Docker Image

```bash
docker build -t codealpha-web .
```

### Verify the Image

```bash
docker images
```

### Run the Docker Container

```bash
docker run -d -p 8080:80 --name codealpha-container codealpha-web
```

### View Running Containers

```bash
docker ps
```

### View All Containers

```bash
docker ps -a
```

### View Container Logs

```bash
docker logs codealpha-container
```

### Inspect the Container

```bash
docker inspect codealpha-container
```

### Stop the Container

```bash
docker stop codealpha-container
```

### Start the Container

```bash
docker start codealpha-container
```

---

## 🌐 Access the Application

After running the container, the website can be accessed at:

```
http://localhost:8080
```

---

## 📚 What I Learned

During this project, I learned:

* Docker image creation using a Dockerfile.
* Building Docker images with the Docker CLI.
* Running and managing Docker containers.
* Port mapping between the host machine and containers.
* Inspecting container information.
* Viewing container logs for troubleshooting.
* Managing the Docker container lifecycle (start, stop, and restart).
* Serving a static website using the Nginx Docker image.

---

## 🚀 Future Improvements

* Deploy the container to a cloud platform.
* Use Docker Compose for multi-container applications.
* Integrate the project into a CI/CD pipeline.
* Add container health checks and monitoring.

---

## 👨‍💻 Author

**Ali Shehzan Punjwani**

Cloud Security Analyst | DevOps & Cloud Computing Enthusiast
