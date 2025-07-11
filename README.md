# Projeto: CI/CD com GitHub Actions e Docker 🐳⚙️

Este projeto mostra como automatizar o build e o push de uma imagem Docker usando GitHub Actions.

## 💡 Objetivo
Subir uma aplicação simples em Flask e publicar sua imagem no Docker Hub automaticamente após cada push no branch `main`.

## 🔧 Tecnologias usadas
- Python 3.11
- Flask
- Docker
- GitHub Actions

## 🚀 Como testar localmente

```bash
docker build -t ci-cd-flask .
docker run -p 5000:5000 ci-cd-flask
