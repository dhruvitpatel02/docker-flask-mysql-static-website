# docker-flask-mysql-static-website

## 🚀 Auto-Deployed Flask + MySQL Web App on AWS EC2 (Using Docker & Shell Scripts)

This project demonstrates how to deploy a simple Python Flask web application with a MySQL backend and custom CSS, using Docker containers. The entire setup is automated and hosted on an AWS EC2 instance.

---

## 🧱 Architecture

→ EC2 Instance → Docker Compose
├── Flask App (Python + HTML/CSS)
└── MySQL Database


---

## 🛠️ Tech Stack

- Python (Flask)
- MySQL
- HTML/CSS (Static Frontend)
- Docker & Docker Compose
- AWS EC2 (Ubuntu 22.04)
- Shell Scripts (for Auto-Deployment)
- GitHub (Code Hosting + Trigger)

---

## 🎯 Features

- Simple Python web app using Flask
- MySQL integration for backend
- Styled frontend with HTML + CSS
- Docker Compose for multi-container setup
- One-command EC2 deployment using shell script
- Fully cloud-native, lightweight, and fast

---

## 📁 Project Structure

<pre> <details> <summary><strong>📁 Project Structure</strong></summary> ```bash . ├── app/ │ ├── app.py # Flask backend │ ├── templates/ │ │ └── index.html # Main HTML page │ └── static/ │ └── style.css # Custom CSS styling ├── db/ │ └── init.sql # Optional: MySQL setup script ├── Dockerfile # Dockerfile for Flask app ├── docker-compose.yml # Compose config for Flask + MySQL ├── deploy.sh # EC2 deployment automation script └── README.md # Documentation (this file) ``` </details> </pre>

