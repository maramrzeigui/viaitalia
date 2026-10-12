<div align="center">

# 🇮🇹 ViaItalia

**Plateforme web d'accompagnement des étudiants qui veulent poursuivre leurs études en Italie.**

![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?logo=nodedotjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/Auth-JWT-000000?logo=jsonwebtokens)

</div>

## ✨ Fonctionnalités

- **Formulaire d'études** : l'étudiant décrit son projet (filière, niveau, ville).
- **Dossier de candidature** : suivi de chaque étape et dépôt des documents.
- **Rendez-vous** : réservation de créneaux avec un conseiller.
- **Contrats et paiements** : génération du contrat et suivi des règlements.
- **Messagerie et notifications** entre l'étudiant et l'équipe.
- **Annonces et informations universitaires** publiées par les administrateurs.
- **Rôles** : étudiant, conseiller et administrateur, avec authentification JWT.
- **Interface animée** : Framer Motion, GSAP et éléments 3D (React Three Fiber).

## 🏗️ Architecture

| Dossier | Contenu |
|---|---|
| `frontend/` | Application React (Headless UI, Heroicons, Framer Motion, GSAP, Three.js) |
| `backend/` | API REST Express : contrôleurs, middlewares d'authentification et de rôles, Prisma + MySQL, envoi d'e-mails |

## 🚀 Lancer le projet

```bash
cd backend && npm install && cp .env.example .env && npx prisma migrate deploy && npm start
cd frontend && npm install && npm start
```

---
👩‍💻 Réalisé par **Maram Rzeigui** · [LinkedIn](https://www.linkedin.com/in/maram-rzeigui/)
