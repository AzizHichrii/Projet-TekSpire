# 🖥️ Plateforme Web Intelligente de Vente et Recommandation de PC

## 📌 Présentation du projet

Ce projet consiste à développer une **application web complète de vente de PC** intégrant des **fonctionnalités d’intelligence artificielle** afin d’offrir une expérience utilisateur avancée et personnalisée.

La plateforme permet :

* L’achat et la vente de PC
* La recommandation intelligente de PC selon les besoins de l’utilisateur
* La prédiction du prix d’un PC à partir de ses caractéristiques

L’application repose sur une architecture moderne **Front-end / Back-end / Machine Learning**, avec des données collectées via **data scraping**.

---

## 🎯 Objectifs du projet

* Créer une plateforme e-commerce spécialisée dans les PC
* Aider l’utilisateur à **choisir le PC le plus adapté** à ses besoins
* Estimer **le prix réel d’un PC** à partir de ses caractéristiques
* Exploiter la **data science** pour améliorer la prise de décision
* Mettre en œuvre une architecture scalable et maintenable

---

## 🏗️ Architecture globale

### 1️⃣ Front-end

* **Technologie** : React.js
* **Fonctionnalités** :

  * Interface utilisateur moderne et responsive
  * Recherche et filtrage des PC
  * Saisie des caractéristiques pour recommandation
  * Formulaire d’estimation de prix
  * Affichage des résultats (PC similaires, prix estimé)

### 2️⃣ Back-end

* **Technologie** : FastAPI
* **Rôles principaux** :

  * Gestion des API REST
  * Communication avec les modèles de Machine Learning
  * Gestion des utilisateurs et des annonces
  * Traitement des requêtes de recommandation et de prédiction

### 3️⃣ Machine Learning

Deux modèles principaux sont intégrés :

#### 🔹 Modèle de recommandation de PC

* Type : **Apprentissage non supervisé / Similarité**
* Objectif : recommander des PC similaires à partir des caractéristiques fournies
* Caractéristiques exploitées :

  * Processeur
  * Mémoire RAM
  * Stockage
  * Carte graphique
  * Marque
  * Prix

#### 🔹 Modèle de prédiction de prix

* Type : **Apprentissage supervisé (régression)**
* Objectif : estimer le prix d’un PC
* Cas d’usage :

  * Utilisateur souhaitant vendre un PC
  * Utilisateur voulant connaître la valeur réelle d’un PC

---

## 📊 Données et Data Scraping

### 🔍 Collecte des données

* Les datasets sont collectés via **web scraping** à partir de sites e-commerce spécialisés
* Données récupérées :

  * Nom du produit
  * Spécifications techniques
  * Prix
  * Marque
  * Description

### 🧹 Prétraitement

* Nettoyage des données
* Normalisation des valeurs numériques
* Encodage des variables catégorielles
* Gestion des valeurs manquantes

---

## ⚙️ Fonctionnalités principales

### 🛒 Vente et consultation de PC

* Liste des PC disponibles
* Détails complets de chaque produit
* Recherche avancée

### 🤖 Recommandation intelligente

* L’utilisateur saisit ses besoins
* Le système propose des PC similaires depuis le dataset

### 💰 Prédiction de prix

* Estimation automatique du prix à partir des caractéristiques
* Aide à la vente et à la négociation

---

## 🧪 Évaluation des modèles

* Métriques utilisées :

  * Silhouette Score (clustering)
  * Inertia
  * RMSE / MAE (régression)
* Ajustement des hyperparamètres

---

## 🔐 Sécurité et bonnes pratiques

* Validation des données côté backend
* Séparation claire des responsabilités
* API REST documentée avec Swagger (FastAPI)

---

## 🚀 Perspectives d’évolution

* Système de comptes utilisateurs
* Historique des recommandations
* Modèle de recommandation hybride
* Dashboard analytique
* Déploiement cloud

---

## 👨‍💻 Auteur

**Aziz Hichri**
Ingénieur logiciel – Génie Logiciel et Systèmes d’Information
Passionné par le développement web, la data science et l’intelligence artificielle

---

## 📄 Licence

Ce projet est développé à des fins académiques et expérimentales.
