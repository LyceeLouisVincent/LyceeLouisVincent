# 🌐 Refonte du site du Lycée Louis Vincent

![Logo du Lycée]([logo.png]) <!-- Remplacer par le chemin du logo -->

## 🚀 Projet : Refonte complète du site internet du Lycée Louis Vincent

Nous sommes une équipe de cinq élèves en Terminale, spécialisés en NSI (Numérique et Sciences Informatiques). Notre mission est de moderniser le site web du Lycée Louis Vincent en refondant totalement son architecture et son design, en utilisant des technologies modernes.

---

### 🎯 Objectifs du projet

- **Amélioration de l'interface utilisateur (UI/UX)** : Mise en place d'une interface moderne et intuitive grâce à **TailwindCSS**.
- **Optimisation des performances** : Utilisation de **Laravel** pour un back-end robuste et efficace.
- **Conception responsive** : Adaptation du site aux formats mobiles et desktop.
- **Nouvelles fonctionnalités** : Ajout de fonctionnalités pratiques pour les élèves, parents et le personnel.
- **Sécurisation** : Protection des données utilisateurs et conformité aux dernières normes de sécurité.

---

### 🛠️ Technologies utilisées

- **Back-end** : Laravel (PHP)
- **Front-end** : HTML5, TailwindCSS
- **Base de données** : MySQL
- **Hébergement** : Interne
- **Versionning** : Git & GitHub

---

### 👥 Équipe de développement

Voici l'équipe derrière ce projet:

- **Développeur 1** : [GitHub Profile](#)
- **Développeur 2** : [GitHub Profile](#)
- **Développeur 3** : [GitHub Profile](#)
- **Développeur 4** : [GitHub Profile](#)
- **Développeur 5** : [GitHub Profile](#)

---

### 📅 Avancement du projet

- **Phase 1** : Analyse des besoins ✔️
- **Phase 2** : Conception des maquettes ✔️
- **Phase 3** : Présentation du projet et validations ⏳
- **Phase 3** : Développement du projet ❌
- **Phase 4** : Tests et validation ❌
- **Phase 5** : Déploiement 🚀

---

## Pré-requis

Avant de commencer, assurez-vous d'avoir les pré-requis suivants installés sur votre machine :

- **PHP** >= 8.0
- **Composer**
- **Node.js** et **npm** (pour la gestion des dépendances front-end)
- **MySQL**

## Étapes d'installation

### 1. Cloner le repository

Clonez ce repository en utilisant la commande suivante :

```bash
git clone https://github.com/username/lycee-louis-vincent.git
```
### 2. Configurer le back-end Laravel
#### a. Accéder au répertoire du back-end :
```bash
cd backend
```
#### b. Installer les dépendances Laravel via Composer :
```bash
composer install
```
#### c. Créer un fichier .env à partir de .env.example et configurer les paramètres de la base de données :
```bash
cp .env.example .env
php artisan key:generate
```
Configurez les détails de connexion à MySQL dans le fichier .env (hôte, nom de la base de données, utilisateur, mot de passe).

#### d. Migrer la base de données :
```bash
php artisan migrate
```
#### e. Lancer le serveur de développement Laravel :
```bash
php artisan serve
```
### 3. Configurer le front-end avec TailwindCSS
#### a. Installer les dépendances TailwindCSS (si applicable) :
```bash
npm install
```
#### b. Lancer la compilation des fichiers Tailwind :
```bash
npm run dev
```
