# TaskForge 🧠
A simple yet scalable task management REST API built with **Spring Boot**, **PostgreSQL**, **Docker**, and **AWS**.  
This project is part of a long-term learning roadmap to master backend engineering and cloud deployment.

---

## 🚀 Features
- CRUD operations for managing tasks (Create, Read, Update, Delete)
- PostgreSQL database integration via Spring Data JPA
- RESTful API with clean architecture
- Docker support for local and cloud deployment
- Ready for CI/CD integration and AWS deployment

---

## 🧱 Tech Stack
| Layer | Technology |
|-------|-------------|
| Backend | Java 17, Spring Boot 3 |
| Database | PostgreSQL |
| Build Tool | Maven |
| Containerization | Docker, Docker Compose |
| Cloud Deployment | AWS EC2, RDS, S3 |
| CI/CD | GitHub Actions (coming soon) |

---

## ⚙️ Setup & Run (Local)
### Prerequisites
- Java 17
- Maven
- PostgreSQL
- Docker (optional but recommended)

### Steps
```bash
# Clone the repository
git clone https://github.com/SEKSEF/taskforge.git
cd taskforge

# Build and run
mvn spring-boot:run