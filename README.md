# DevOps Enabled Full Stack Web Application with CI/CD

This repository contains a **full-stack web application** deployed using a **CI/CD pipeline**, **Docker containers**, and **cloud infrastructure** provisioning on **AWS EC2**. The system includes frontend, backend, and database containers communicating seamlessly, automated through Jenkins and Terraform.

---

##  Features

- **CI/CD Pipeline**:  Docker image build, and deployment using Jenkins and GitHub  
- **Containerization**: Frontend, backend, and database services packaged using Docker  
- **Cloud Infrastructure**: AWS EC2 instances provisioned via Terraform for hosting containers  
- **Microservices Architecture**: Independent services for scalability, flexibility, and maintainability  
- **Database**: MongoDB database integration  

---

##  Architecture Overview

The project follows a microservices based architecture

- **Frontend (React)** → Handles user interface  
- **Backend (Node.js)** → API & business logic  
- **Database (MongoDB)** → Persistent storage  
- **AWS EC2** → Hosts the containers deployed via Terraform  
- Containers communicate through an internal network for seamless operations  

---

##  Tech Stack

| Component | Technology | 
|-----------|------------|
| Frontend  | React      |
| Backend   | Node.js    | 
| Database  | MongoDB  | 
| CI/CD     | Jenkins   | 
| Containerization | Docker | 
| Infrastructure as Code | Terraform | 
| Cloud Hosting | AWS EC2 | 

---

##  Screenshots

**1. CI/CD Pipeline**  
<img width="1920" height="1020" alt="Screenshot 2026-03-25 205034" src="https://github.com/user-attachments/assets/4d77ffc0-06ac-4816-8664-87cf0f2ea400" />


**2. Web Application UI**  
<img width="1916" height="1012" alt="Screenshot 2026-02-14 151405" src="https://github.com/user-attachments/assets/206d473a-25f9-46fa-9d3e-d78d9caf61d1" />


**3. Architecture Diagram**  
  <img width="1286" height="384" alt="Untitled Diagram drawio" src="https://github.com/user-attachments/assets/00cb3a96-8b2e-4a20-ba5c-d436b0410667" />

---

##  Getting Started

### Prerequisites
- Node.js v24.13.0
- React v18.2.0
- Docker & Docker Compose
- Terraform
- AWS account with EC2 permissions
