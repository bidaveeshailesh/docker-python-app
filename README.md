# Docker Python Application

## 📌 Project Overview

This project demonstrates how to **containerize a Python application using Docker**.

The application is packaged with its required environment and dependencies so that it can run consistently across different systems.

## 🏗️ Architecture

```text id="y2n8pc"
Python Application
       |
       v
 Dockerfile
       |
       v
 Docker Image
       |
       v
 Docker Container
       |
       v
 Running Python Application
```

## 🛠️ Technologies Used

- Python
- Docker
- Dockerfile
- Git & GitHub
- Linux

## ⚙️ How It Works

1. Create the Python application.
2. Create a `Dockerfile`.
3. Define the Python environment and application dependencies.
4. Build a Docker image.
5. Create a container from the image.
6. Run the Python application inside the container.
7. Test the application.

## 🐳 Example Docker Commands

```bash
docker build -t python-app .
```

```bash
docker run python-app
```

To view running containers:

```bash
docker ps
```

## 📂 Project Structure

```text id="u7r4de"
docker-python-app/
│
├── Dockerfile
├── app.py
└── README.md
```

## 🎯 What I Learned

- Python application containerization
- Docker images and containers
- Writing a Dockerfile
- Building Docker images
- Running containers
- Basic Docker commands
- Application deployment concepts
- GitHub project documentation

## 📂 Project Type

**Python / Docker / Containerization / DevOps**

## 👨‍💻 Author

**Shailesh Bidave**

GitHub: [@bidaveeshailesh](https://github.com/bidaveeshailesh)
