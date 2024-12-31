# Backend Node.js, Express et MongoDB

Ce repository contient le dossier **backend** développé dans le cadre du cours ["Passez au Full Stack avec Node.js, Express et MongoDB"](https://openclassrooms.com/fr/courses/6390246-passez-au-full-stack-avec-node-js-express-et-mongodb) proposé par OpenClassrooms.

## À propos du cours
Ce cours est axé sur la pratique et l'apprentissage du **développement backend** avec les technologies suivantes :

- **Node.js** : Environnement d'exécution JavaScript côté serveur.
- **Express.js** : Framework pour créer des applications web.
- **MongoDB** : Base de données NoSQL orientée document.

> **Important** : Le cours se concentre exclusivement sur le backend. Ainsi, seul le dossier backend est présent dans ce repository. 

## Contenu du repository

Ce repository inclut :
- Le code backend implémentant des fonctionnalités telles que la création d'API RESTful, la gestion des utilisateurs, et la persistance des données avec MongoDB.

Le frontend n'a pas été développé dans le cadre de ce cours et n'est donc pas inclus.

## Comment exécuter le projet ?

### Prérequis
- Node.js installé ([Télécharger ici](https://nodejs.org/))
- MongoDB configuré ([Documentation officielle](https://www.mongodb.com/docs/))

### Étapes
1. **Cloner le repository** :
   ```bash
   git clone <url-du-repository>
   cd <nom-du-repository>
   ```

2. **Installer les dépendances** :
   ```bash
   npm install
   ```

3. **Configurer les variables d'environnement** :
   Créez un fichier `.env` à la racine du dossier backend et ajoutez les informations nécessaires (exemple ci-dessous) :
   ```env
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/votre-base
   JWT_SECRET=votre-secret
   ```

4. **Lancer le serveur** :
   ```bash
   npm start
   ```

Le serveur sera accessible sur `http://localhost:3000` par défaut.

## Objectifs pédagogiques atteints
- Comprendre les bases de la création d'API avec **Node.js** et **Express**.
- Mettre en place une base de données **MongoDB** et manipuler les données.
- Gérer l'authentification avec des tokens **JWT**.

## Licence
Ce projet est réalisé dans le cadre d'une formation. Vous êtes libre de vous en inspirer, mais il ne doit pas être utilisé à des fins commerciales sans autorisation.

---

Merci à [OpenClassrooms](https://openclassrooms.com) pour la qualité de leur formation !
