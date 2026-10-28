# Projet 001 — CV avec React et Vite

Ce projet consiste à créer un CV en utilisant React et Vite.
Le CV est composé de trois composants principaux :
* InfoPerso : informations personnelles
* Competences : compétences
* Experiences : expériences

# Création du projet
Le projet a été créé avec Vite.
Commande utilisée:
npm create vite@latest 001
Lors de la création du projet, les choix suivants ont été effectués :
* Framework : React
* Variant : JavaScript
* Linter : ESLint
Ensuite, les dépendances ont été installées avec :
npm install
Pour lancer le projet en mode développement :
npm run dev
Le projet est ensuite accessible avec l’adresse indiquée par Vite, par exemple :
http://localhost:5173/

# Organisation du projet
Le projet possède plusieurs dossiers et fichiers importants.

1. node_modules
Ce dossier contient les dépendances et les bibliothèques nécessaires au fonctionnement du projet.
Il est automatiquement créé après l’installation avec :
npm install

2. public
Ce dossier contient les fichiers statiques qui peuvent être utilisés directement dans l’application.

3. src
C’est le dossier principal dans lequel se trouve le code source de l’application React.
Dans ce projet, le dossier src contient notamment :

* components
* App.jsx
* App.css
* index.css
* main.jsx

4. src/components
Ce dossier contient les composants React créés pour le CV.
Il contient :

* InfoPerso.jsx
* Competences.jsx
* Experiences.jsx

# Rôle des fichiers principaux

a. App.jsx
App.jsx est le composant principal de l’application.
Il importe les trois composants du CV et les affiche :

* InfoPerso
* Competences
* Experiences

b. main.jsx
main.jsx est le point d’entrée de l’application React.
Il permet de charger le composant App dans la page HTML.

c. index.html
index.html est la page HTML principale de l’application.
Elle contient notamment l’élément dans lequel l’application React est affichée.

d. package.json
package.json contient les informations du projet ainsi que les dépendances et les scripts utilisés pour lancer l’application.
Par exemple :
__npm run dev
permet de lancer le serveur de développement.

e. package-lock.json
Ce fichier permet de conserver les versions précises des dépendances installées dans le projet.

f. vite.config.js
Ce fichier contient la configuration de Vite utilisée par le projet.

g. eslint.config.js
Ce fichier contient la configuration d’ESLint, qui permet de détecter certaines erreurs et problèmes dans le code JavaScript.

h. gitignore
Ce fichier indique les fichiers et dossiers qui ne doivent pas être pris en compte par Git, comme certains fichiers générés automatiquement.

# Création des composants
Trois composants ont été créés dans le dossier src/components.
-InfoPerso.jsx
Ce composant affiche les informations personnelles du CV :

* Nom
* Prénom
* Formation
* Email
* Téléphone

-Competences.jsx
Ce composant affiche les différentes compétences sous forme de liste.

-Experiences.jsx
Ce composant présente les expériences et projets réalisés.

# Assemblage des composants
Les trois composants sont importés dans App.jsx.

import InfoPerso from "./components/InfoPerso";
import Competences from "./components/Competences";
import Experiences from "./components/Experiences";

Ils sont ensuite affichés dans le composant principal :

<InfoPerso />
<Competences />
<Experiences />

# Lancement du projet
Pour lancer le projet, ouvrir un terminal dans le dossier 001 puis exécuter :
npm run dev
Vite démarre alors un serveur local permettant d’afficher le CV dans le navigateur.

# Résultat
Le CV final est composé de trois parties :

1. Informations personnelles
2. Compétences
3. Expériences

Le projet utilise React, JavaScript et Vite.