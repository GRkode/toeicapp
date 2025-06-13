# 📘 TOEIC Reading Practice Platform

Une plateforme web permettant de s'entraîner aux parties **5** (QCM) et **6** (textes à trous) du test TOEIC Reading. Le projet est conçu avec **Angular**, **Spring Boot**, **PostgreSQL**, et intègre **Docker**, **GitHub Actions**, et **Kubernetes** dans un objectif de montée en compétence vers un profil sénior.

---

## 🧱 Technologies principales

| Frontend    | Backend       | Base de données | DevOps / Tests                 |
|-------------|---------------|------------------|-------------------------------|
| Angular     | Spring Boot   | PostgreSQL       | Docker, GitHub Actions, Postman |
| Nginx       | Spring Security + JWT |            | Kubernetes (à venir), Swagger  |

---

## 🔍 Fonctionnalités du MVP

- 🔐 Authentification avec JWT (email + mot de passe)
- 🧠 Passage de tests TOEIC Partie 5 (QCM)
- 📄 Passage de tests Partie 6 (texte à trous)
- 📊 Affichage des résultats et explications
- 🗃️ Historique des sessions de test
- 🐳 Conteneurisation Docker
- ⚙️ Intégration continue avec GitHub Actions

---

## 🚀 Lancement rapide (en local)

### 1. Prérequis

- Docker & Docker Compose
- Java 17
- Node.js + Angular CLI
- PostgreSQL (ou utiliser Docker)

### 2. Lancer avec Docker Compose

```bash
docker-compose up --build
