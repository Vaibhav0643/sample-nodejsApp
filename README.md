# 🚀 CI/CD Pipeline using GitHub Actions

This project demonstrates an automated **CI/CD pipeline** that builds and deploys a sample **Node.js web application** using **GitHub Actions** and **DockerHub**.

---

## 🧰 Tech Stack
- **Node.js** – Sample web app  
- **Docker** – Containerization  
- **GitHub Actions** – CI/CD automation  
- **DockerHub** – Image registry  

---

## ⚙️ Pipeline Workflow
The pipeline (defined in `.github/workflows/main.yml`) performs the following steps automatically on every **push to the main branch**:

1. Checkout source code  
2. Install dependencies  
3. Run basic tests  
4. Build Docker image  
5. Push image to **DockerHub**

---

## 📸 Screenshots
All execution proofs and workflow run screenshots are available inside the [`Screenshots/`](./Screenshots) folder.

---

## 🧾 Deliverable Summary
- Automated CI/CD using GitHub Actions  
- Node.js web app containerized with Docker  
- Docker image pushed to DockerHub  
- Workflow triggered on `push` to `main`

---

**Author:** *Vaibhav Agarwal*  
