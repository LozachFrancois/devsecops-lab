# 🔒 DevSecOps Pipeline - Secure Node.js App

## 📌 Description

Projet de sécurisation d’une application Node.js avec mise en place d’un pipeline DevSecOps complet.

## ⚙️ Stack

- Node.js
- Docker
- GitHub Actions
- Semgrep (SAST)
- npm audit (SCA)
- Gitleaks (Secrets)
- Trivy (Container Scan)

## 🚀 Installation

```bash
git clone https://github.com/<user>/<repo>.git
cd devsecops-lab
cp .env.example .env
docker build -t secure-app .
docker run -p 3000:3000 secure-app
