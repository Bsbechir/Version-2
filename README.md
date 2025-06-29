
# Bankily App – Interface de Saisie Multilingue Sécurisée

Cette application Streamlit permet de saisir, suivre et gérer les données financières des points de services Bankily, Sedad et Masrivi.

## 🔐 Fonctionnalités principales

- Connexion par **code sécurisé**
- Interface **multilingue** (Français 🇫🇷 / Arabe 🇸🇦)
- Affichage **RTL** automatique pour l’arabe
- Interface **différenciée** :
  - **Admin** : gestion des agents, points, capital et saisies
  - **Agent** : saisie journalière uniquement
- Calcul automatique de **statut** (OK / erreur capital)
- Gestion des **opérateurs multiples** par point

## 📁 Fichiers inclus

- `interface_bankily.py` – code principal de l'application
- `user.csv` – liste des utilisateurs (code, langue, rôle)
- `point.csv` – liste des points (nom, agent, capital, opérateurs)
- `saisies.csv` – historique des saisies
- `requirements.txt` – dépendances Python

## 🚀 Déploiement local

1. Installe les dépendances :
```bash
pip install -r requirements.txt
```

2. Lance l'app :
```bash
streamlit run interface_bankily.py
```

## ☁️ Déploiement Streamlit Cloud

1. Pousse les fichiers sur GitHub
2. Connecte le repo sur https://streamlit.io/cloud
3. Déploie automatiquement ton app

---

## ✍️ Créé par Bechir pour une gestion fluide des points de services Bankily/Sedad/Masrivi
