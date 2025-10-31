# mesressources

# Cahier des charges – Projet *Mes Ressources*

---

## 1. Contexte du projet
Le projet **« Mes Ressources »** a pour but de créer une **plateforme interne de partage de ressources pédagogiques**, permettant aux apprenants et formateurs de l’école **AFEC Bayonne** d’accéder facilement à l’ensemble des supports de cours (articles, documents, vidéos, liens externes, etc.).

L’objectif est de **centraliser toutes les ressources** dans un espace unique, accessible uniquement aux membres autorisés.  
Le site proposera également une **interface d’administration** permettant aux rédacteurs de gérer les contenus et les comptes utilisateurs.

---

## 2. Objectifs du projet
- Créer un site web **dynamique et responsive** présentant l’ensemble des ressources de cours.  
- Permettre aux utilisateurs de **consulter les contenus pédagogiques** selon leur rôle.  
- Offrir un **système de connexion sécurisée** pour restreindre l’accès au site.  
- Fournir un **espace d’administration** pour la gestion des ressources et des utilisateurs.  
- Garantir une **expérience utilisateur claire, fluide et ergonomique**.

---

## 3. Profil du client
Le client est **l’AFEC Bayonne**, une école de formation en développement web souhaitant mettre à disposition de ses étudiants et formateurs une plateforme centralisée de partage de cours.  
Le site doit être **simple à utiliser**, **rapide à déployer** et **facile à maintenir**.

---

## 4. Utilisateurs cibles

| Type d’utilisateur | Description | Droits principaux |
|--------------------|--------------|-------------------|
| **Utilisateur (étudiant)** | Membre de l’école disposant d’un compte de connexion | - Se connecter<br>- Consulter les ressources disponibles |
| **Rédacteur (formateur)** | Membre disposant de droits avancés pour enrichir le site | - Ajouter, modifier ou supprimer des ressources<br>- Créer de nouveaux comptes utilisateurs |
| **Administrateur** | Responsable technique du site | - Gérer les utilisateurs et leurs rôles<br>- Superviser l’ensemble du contenu |

---

## 5. Besoins fonctionnels

### 5.1 Authentification
- Page de connexion avec vérification des identifiants (email / mot de passe).  
- Accès aux ressources uniquement après connexion.  
- Possibilité de déconnexion.  
- Interface d’erreur en cas de mauvais identifiants.

### 5.2 Gestion des utilisateurs
- Les rédacteurs peuvent créer de nouveaux comptes utilisateurs.  
- Chaque compte a un rôle défini (**utilisateur** ou **rédacteur**).  
- Gestion simple des profils : nom, email, rôle, mot de passe.

### 5.3 Publication et gestion des contenus
- Création d’une nouvelle ressource (titre, description, catégorie, auteur, média, date).  
- Modification et suppression d’une ressource par son rédacteur.  
- Organisation des ressources par **catégories** (Front-End, Back-End, JavaScript, etc.).  
- Ajout possible de **médias** : PDF, images, liens, vidéos.

### 5.4 Consultation des ressources
- Page listant l’ensemble des ressources.  
- Filtres ou recherche par **titre**, **catégorie** ou **auteur**.  
- Affichage clair et responsive sous forme de **cartes**.  
- Fiche détaillée pour chaque ressource.

### 5.5 Administration
- Tableau de bord simple pour les rédacteurs.  
- Gestion des contenus et des utilisateurs.  
- Messages de confirmation pour les actions (ajout, modification, suppression).

---

## 6. Contraintes techniques

| Domaine | Exigence |
|----------|-----------|
| **Langages** | HTML5, CSS3, JavaScript |
| **Organisation du code** | Modules JavaScript séparés (`main.js`, `data.js`, `auth.js`...) |
| **Responsive design** | Compatible desktop, tablette et mobile |
| **Charte graphique** | Thème sombre : fond sombre, texte blanc, accent bleu, alerte rouge |
| **Inspiration visuelle** | Interface claire et moderne, inspirée du site [SoloLearn](https://www.sololearn.com/) |

---

## 7. Planning prévisionnel

| Phase | Objectifs | Durée estimée |
|--------|------------|----------------|
| **Phase 1 : Cahier des charges** | Définir le besoin, les utilisateurs et les fonctionnalités | 1 semaine |
| **Phase 2 : Structure HTML/CSS** | Créer les pages, la navigation et le design responsive | 1 à 2 semaines |
| **Phase 3 : Dynamique locale (JavaScript)** | Manipulation du DOM, affichage dynamique des données locales | 1 semaine |
| **Phase 4 : Modularisation** | Séparation du code en modules JS | 1 semaine |
| **Phase 5 : Intégration d’API** | Connexion à une API externe (requêtes, tokens, sécurité) | 1 à 2 semaines |
| **Phase 6 : Tests et documentation** | Vérification, corrections et préparation du livrable | 1 semaine |

---

## 8. Livrables attendus
- Cahier des charges fonctionnel (présent document).  
- Arborescence et structure HTML/CSS du site.  
- Version fonctionnelle locale avec données statiques (JS / JSON).  
- Version dynamique connectée à une API distante.  
- Documentation technique (structure du code, API utilisée, gestion des rôles).  
- Présentation orale ou écrite du projet final.

---

