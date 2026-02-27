# Personal Portfolio – DevOps Project

Personal portfolio website presenting my profile, skills and projects.

This project was built as part of a **DevOps course assignment** and demonstrates a full deployment pipeline using Docker, GitHub Actions and a cloud server.

---

## Live Website

🌐 https://hasonatet12.duckdns.org/

---

## About the Project

This portfolio website presents:

- Personal introduction
- Technical skills
- Links to GitHub projects
- Professional profile

The website is deployed automatically using a **CI/CD pipeline**.

---

## Technologies Used

- HTML
- CSS
- Docker
- Docker Compose
- GitHub Actions
- Nginx
- Linux (Ubuntu Server)

---

## DevOps Architecture

The project demonstrates the following DevOps workflow:

Developer → GitHub → GitHub Actions → DockerHub → Cloud Server → Nginx → Live Website

---

## CI/CD Pipeline

Every push to the repository triggers a GitHub Actions workflow that:

1. Builds a Docker image
2. Pushes the image to DockerHub
3. Connects to the cloud server via SSH
4. Pulls the new Docker image
5. Restarts the container automatically

---

## Docker Deployment

The site runs inside a Docker container using **Nginx**.

Example run using Docker Compose:

```bash
docker compose up -d --build


## Project Structure

```
portfolio
│
├── index.html
├── style.css
├── Dockerfile
├── docker-compose.yml
└── .github/workflows
```

---

## Author

**Teto Hassuna**

DevOps | Docker | Node.js | Linux

GitHub:  
https://github.com/hasonateto12
