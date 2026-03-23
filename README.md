# learn-audit-iso2700x
Simulateur d'Audit de Sécurité ISO 2700x

# 🏢 Learn=>Audit : Simulateur d'Audit ISO 2700x

> Application web interactive pour former les futurs auditeurs à la conformité ISO 27001, ISO 27002 et ISO 27005.

![Status](https://img.shields.io/badge/Statut-En%20développement-yellow)
![ISO](https://img.shields.io/badge/ISO-27001%20%7C%2027002%20%7C%2027005-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Description

**Learn=>Audit** est un simulateur d'audit de sécurité des systèmes d'information. Il guide l'utilisateur à travers un scénario d'audit de conformité ISO 2700x pour une entreprise fictive, en simulant les étapes clés : collecte de preuves, évaluation des contrôles, gestion des risques et génération de rapport.

---

## 👥 Équipe

| Membre | Rôle |
|--------|------|
| **Salma** | Chef de Projet & DevOps |
| **Amina** | Backend Senior |
| **Oumaima** | Backend Junior |
| **Sara** | Frontend Senior |
| **Fati** | Frontend Junior |
| **Majda** | Contenu & Documentation |

---

## 🗂️ Structure du Projet

```
learn-audit-iso2700x/
├── backend/
│   ├── app/
│   │   ├── models/          # Modèles BDD (User, Audit, Control, Finding...)
│   │   ├── routes/          # Endpoints API RESTful
│   │   ├── services/        # Logique métier
│   │   └── utils/           # Authentification JWT, helpers
│   ├── tests/               # Tests unitaires backend
│   ├── requirements.txt
│   └── README.md
├── frontend/
│   ├── src/
│   │   ├── components/      # Composants réutilisables
│   │   ├── pages/           # Pages (Accueil, Dashboard, Contrôle, Rapport)
│   │   ├── assets/          # Images, icônes, styles
│   │   └── utils/           # Appels API, helpers
│   ├── public/
│   └── package.json
├── docs/
│   ├── architecture.md      # Architecture technique
│   ├── api-swagger.yaml     # Documentation API
│   ├── bdd-schema.pdf       # Schéma base de données
│   └── guide-utilisateur.md # Guide d'utilisation
├── .github/
│   └── workflows/
│       └── ci.yml           # Pipeline CI/CD GitHub Actions
├── .gitignore
└── README.md
```

---

## 🚀 Fonctionnalités

- 🏢 **4 scénarios d'entreprise** fictive (PME, e-commerce, santé, industrie)
- 📋 **20 contrôles ISO 27002** avec descriptions et objectifs
- 🔍 **Collecte de preuves simulées** (politiques, logs, configurations)
- ✅ **Évaluation de conformité** avec justification
- ⚠️ **Matrice de risque interactive** (ISO 27005)
- 📊 **Rapport d'audit automatique** avec score et recommandations
- 📈 **Graphiques statistiques** (Chart.js)

---

## 🛠️ Technologies

| Couche | Technologies |
|--------|-------------|
| **Backend** | Python (Flask/Django), JWT |
| **Base de données** | PostgreSQL / SQLite |
| **Frontend** | HTML5, CSS3, JavaScript (React/Vue) |
| **Graphiques** | Chart.js |
| **API Docs** | Swagger / OpenAPI |
| **CI/CD** | GitHub Actions |
| **Déploiement** | Heroku / Railway |

---

## ⚙️ Installation & Déploiement

### Prérequis
- Python 3.10+
- Node.js 18+
- PostgreSQL (ou SQLite pour le dev)

### Backend
```bash
cd backend
pip install -r requirements.txt
python app.py
```

### Frontend
```bash
cd frontend
npm install
npm start
```

### Variables d'environnement
Créer un fichier `.env` à la racine du backend :
```
SECRET_KEY=your_secret_key
DATABASE_URL=postgresql://user:password@localhost/learnaudit
JWT_SECRET=your_jwt_secret
```

---

## 📅 Planning

| Semaine | Phase | Objectif |
|---------|-------|----------|
| S1 | Conception | GitHub, Trello, BDD, Maquettes, Scénarios ISO |
| S2 | Développement Core | API, Auth, Frontend pages principales |
| S3 | Intégration | Intégration API, modules conformité, déploiement staging |
| S4 | Tests & Présentation | Tests, corrections, documentation, soutenance |

---

## 📄 Livrables

- [ ] Application web fonctionnelle déployée
- [ ] Documentation technique complète
- [ ] Rapport de projet final
- [ ] Présentation orale (12-15 slides)

---



