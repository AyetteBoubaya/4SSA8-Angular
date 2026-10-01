# Application côté client — Angular

Projet réalisé dans le cadre du module **Application côté client** à **ESPRIT**, en 4ème année du cycle ingénieur informatique.

L'objectif du module est de maîtriser un framework de développement côté client et de concevoir une application web côté client basée sur une architecture de type **Single Page Application (SPA)**.

## 🛠️ Technologies utilisées

* **Angular**
* **TypeScript**
* **HTML / CSS**
* **Node.js**
* **npm**

## 📚 Concepts abordés

Ce projet permet de mettre en pratique les principaux concepts étudiés dans le module :

### Composants

* Structure d'un projet Angular
* Création et manipulation de composants
* Architecture orientée composants
* Composants réutilisables
* Cycle de vie des composants

### Data Binding & Directives

* Interpolation
* Property Binding
* Event Binding
* Two-way Data Binding
* Directives structurelles et d'attributs
* Pipes prédéfinies

### Services & Injection de dépendances

* Création de services
* Injection de dépendances
* Partage de données entre composants
* Utilisation de `Router` et `ActivatedRoute`

### Routing

* Routage statique et dynamique
* Création de routes et de liens
* Paramètres de route
* Navigation entre les différentes vues
* Lazy Loading

### Formulaires

* Création de formulaires Angular
* Reactive Forms
* Validation des formulaires
* Utilisation de `FormBuilder`

### Communication avec le backend

* Utilisation de `HttpClient`
* Requêtes HTTP
* Consommation de Web Services
* Communication entre l'application Angular et le backend

### Interceptors

* Création d'interceptors HTTP
* Interception des requêtes
* Ajout d'un token d'authentification
* Gestion de l'authentification avec un token JWT

## 📁 Structure du projet

```text
src/
├── app/
│   ├── components/
│   ├── services/
│   ├── models/
│   ├── pages/
│   ├── app.routes.ts
│   └── app.component.*
│
├── assets/
├── environments/
└── main.ts
```

> La structure peut évoluer selon les besoins du projet et les fonctionnalités développées.

## 🚀 Installation

### Prérequis

Avant de lancer le projet, assurez-vous d'avoir installé :

* Node.js
* npm
* Angular CLI

### Installation des dépendances

```bash
npm install
```

### Lancer l'application

```bash
ng serve
```

Puis ouvrir :

```text
http://localhost:4200/
```

## 🎯 Objectifs pédagogiques

À travers ce projet, les objectifs sont notamment de :

* Comprendre l'architecture d'une application frontend.
* Maîtriser les composants Angular.
* Implémenter la navigation entre les différentes vues.
* Utiliser les services et l'injection de dépendances.
* Structurer une application en composants indépendants et réutilisables.
* Créer et valider des formulaires réactifs.
* Consommer des services backend via HTTP.
* Mettre en place un interceptor pour l'authentification.

## 👩‍💻 Auteur

**Ayette Boubaya**

Étudiante en 4ème année du cycle ingénieur informatique — **ESPRIT**

## 📖 Références

* [Angular](https://angular.io)
* [Node.js](https://nodejs.org/en/)
* [TypeScript](https://www.typescriptlang.org/)
* [npm](https://www.npmjs.com/)
