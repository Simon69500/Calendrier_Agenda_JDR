# 📅 Calendrier & Agenda JDR 🎲 (🚧 En cours de développement 🚧)
![Status](https://img.shields.io/badge/Status-En%20cours%20de%20développement-orange)

**Calendrier & Agenda JDR** est une application conçue pour aider les **Maîtres du Jeu (MJ)** et les **joueurs de jeux de rôle (JDR)** à organiser et gérer leurs campagnes de manière efficace. Grâce à une interface intuitive et un calendrier interactif, il permet de planifier des sessions, suivre la progression des parties et faciliter la communication entre les joueurs.

---

## 📌 Contexte du projet  

Ce projet est développé dans le cadre de l'obtention du titre **RNCP 5 "Développeur Web et Mobile - Full Stack"**.  
L’application cible les amateurs de **Donjon & Dragon (D&D)**, leur offrant une solution numérique moderne pour la gestion des campagnes et sessions de jeu.

🔹 **Objectif** :  
Fournir un outil numérique **pratique et intuitif** pour la gestion des campagnes, avec des fonctionnalités adaptées aux besoins des joueurs et des maîtres du jeu.

---

## 🎨 Maquettes & Cahier des Charges  

📄 **Cahier des charges** : [À venir]  
🎨 **Maquettes Figma** : [Voir les maquettes](https://www.figma.com/community/file/1471108066721575588)  

---

## 🛠️ Technologies Utilisées  

### Frontend
- **Angular 19** - Framework moderne pour le développement frontend  
- **SCSS** - Stylisation avancée et modulaire
- **Bootstrap** - Composant UI et responsifs  
- **Angular Material** - Composants UI élégants et responsifs  

### Backend
- **Symfony 6** - Framework PHP pour la logique serveur  
- **MySQL** - Base de données relationnelle pour gérer utilisateurs, campagnes et événements  
- **JWT** - Authentification sécurisée des utilisateurs  

---

## ⚙️ Fonctionnalités Principales  

### 🏰 Gestion des campagnes
- Création de campagnes avec un **nom, description et date**  
- Suivi des campagnes en cours et terminées  
- Gestion des sessions : **planification et suivi des joueurs**  
- Ajout de **résumés et notes** après chaque session  

### 📅 Calendrier partagé
- Affichage des événements sous **vue mensuelle/hebdomadaire**  
- **Notifications automatiques** pour les sessions à venir  
- Ajout de **notes et résumés** pour chaque événement  

### 🎨 Interface utilisateur dynamique
- **Responsive** (PC, tablette, mobile)  
- **Navigation fluide** avec **menu latéral et modals interactifs**  
- **Feedback visuel** : confirmation des actions, erreurs, animations  

### ✉️ Formulaires interactifs
- **Formulaire de contact** avec validation des champs  
- **Formulaire de connexion/inscription** sécurisé  
- Cryptage des **mots de passe** pour protéger les données des utilisateurs  

---

## 🚀 Installation & Exécution  

### Prérequis
- Node.js v20+  
- Angular CLI  
- Composer (pour Symfony)  
- MySQL ou équivalent  

### Frontend
```bash
cd front
npm install
ng serve
```
Accès via http://localhost:4200

### Backend
```bash
cd back
composer install
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
symfony server:start
```
Accès via http://localhost:8000

### 🔧 Scripts Angular utiles
```ng serve``` : lance le serveur de développement

```ng build``` : compile l’application pour la production

```ng test``` : lance les tests unitaires

## 📁 Structure du projet 
```lua
front/
│-- src/app/
│   │-- core/        # Services globaux, modèles, interceptors
│   │-- features/    # Pages principales (Home, Créer campagne, Dashboard, Contact)
│   │-- shared/      # Composants réutilisables (Header, Footer, Modals, Buttons)
│-- assets/          # Images, icônes, polices
│-- app-routing.module.ts
│-- app.config.ts
│-- app.component.ts/.html/.scss

back/
│-- src/             # Code Symfony
│-- migrations/      # Scripts de migration de la base
│-- config/          # Configuration Symfony

```
### 📞 Contact
📧 Email : simonsola67@gmail.com
🔗 LinkedIn : Simon Badin
