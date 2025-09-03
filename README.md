# Flask + Redis Web App with Docker Compose

## 📌 Overview
This project demonstrates how to containerize a simple Python Flask web application and connect it with a Redis cache using Docker Compose.  
The web app counts the number of times it has been accessed.

---

## ⚙️ Setup & Execution Steps

```bash
# 1. Build and start the containers
docker compose up --build

# 2. Open the application in your browser
http://localhost:8000

# 3. Stop the containers
docker compose down
