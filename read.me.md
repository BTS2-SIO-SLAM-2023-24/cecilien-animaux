# Mon Projet Animauxcompagnie


Bienvenue dans mon projet Animauxcompagnie. Ce projet est une application web qui gère une liste d'animaux de compagnie et permet de les affecter aux employés.
Ce projet est une application de gestion d'animaux de compagnie pour une entreprise qui prête des animaux à ses employés pour améliorer leur bien-être au travail. 


L'application est développée en utilisant Node.js, Express.js, MongoDB, et TypeScript pour le backend, et JavaScript pur (Vanilla JavaScript) pour le frontend.


## Structure du Projet


Le projet est organisé en deux parties principales : le backend (API RESTful) et le frontend.


### Backend (API)


Le backend est construit avec Node.js et Express.js pour créer une API RESTful en utilisant TypeScript. Il gère les données relatives aux animaux et aux employés.


- Le code source du backend se trouve dans le répertoire `api/src`.
- Les schémas de données sont définis dans le dossier `models`.
- Les routes de l'API sont gérées dans le dossier `routes`.
- Le serveur Express est configuré dans `server.ts`.
- Pour installer les dépendances du backend, exécutez `npm install` dans le répertoire `api`.
- Pour démarrer le serveur backend, utilisez `npm start` dans le répertoire `api`.


#### Configuration de Mongoose


Mongoose est utilisé pour interagir avec la base de données MongoDB. Assurez-vous de configurer Mongoose pour votre base de données dans le fichier `db.js`.


#### Exemple de Contrôleur


Un exemple de contrôleur pour la création d'un nouvel animal est fourni dans `controllers/animalController.ts`






### Frontend - Structure du Répertoire


Ce répertoire contient la partie Frontend de notre projet de gestion d'animaux de compagnie. Le frontend est développé en utilisant JavaScript pur (Vanilla JavaScript) pour fournir une interface utilisateur pour gérer les animaux et les employés.


 Frontend /
|-- node_modules/
|-- public/
| |-- index.html
|-- src/
| |-- components/
| | |-- AnimalList.js
| | |-- EmployeeList.js
| |-- App.js (ou votre code front-end)
|-- package.json
|-- tsconfig.json
|-- README.md


- Le code source du frontend se trouve dans le répertoire `client/src`.
- Pour installer les dépendances du frontend, exécutez `npm install` dans le répertoire `client`.
- Pour démarrer l'application frontend, utilisez `npm start` dans le répertoire `client`.




- **`node_modules/`** : Répertoire contenant les dépendances du projet installées via npm.


- **`public/`** : Ce répertoire contient les fichiers statiques, notamment le fichier `index.html` qui est la page principale de votre application.


- **`src/`** : Le code source de votre application est stocké ici.


  - **`components/`** : Les composants réutilisables de votre application sont stockés ici. Par exemple, `AnimalList.js` et `EmployeeList.js` sont des composants pour afficher la liste des animaux et des employés.


  - **`App.js`** : Le point d'entrée de votre application front-end. Vous pouvez y ajouter votre logique principale ou organiser votre application comme vous le souhaitez.


- **`package.json`** : Le fichier de configuration pour les dépendances du projet côté client.




## Comment utiliser Lite Server


Lite Server est un serveur web léger qui vous permet de tester votre application localement pendant le développement. Voici comment l'utiliser :


1. Assurez-vous d'avoir Node.js et npm installés sur votre système.
2. Installez Lite Server en utilisant la commande suivante dans le répertoire `client/` :


Lite Server démarrera le serveur et ouvrira automatiquement votre application dans le navigateur par défaut. Il surveillera également les modifications de vos fichiers source et rechargera automatiquement la page pour vous montrer les résultats en temps réel.


## À Propos de Lite Server


Lite Server est un serveur web minimaliste conçu pour le développement d'applications web côté client. Il est léger, facile à configurer et offre des fonctionnalités telles que le rechargement automatique de la page lors de la modification des fichiers source. C'est un outil idéal pour le développement local de votre application front-end.




## Configuration


- Le fichier `tsconfig.json` à la racine du projet contient des configurations globales TypeScript pour l'ensemble du projet.
- Les fichiers `tsconfig.json` dans les répertoires `api` et `client` contiennent des configurations spécifiques pour le backend et le frontend respectivement.


## Installation


1. Clonez ce dépôt : `git clone https://github.com/votre-utilisateur/mon-projet.git`.
2. Installez les dépendances du backend : `cd api && npm install`.
3. Installez les dépendances du frontend : `cd client && npm install`.


## Utilisation


1. Démarrer le serveur backend : `cd api && npm start`.
2. Démarrer l'application frontend : `cd client && npm start`.


Le frontend sera accessible à l'adresse http://localhost:4200.
- Accédez à l'interface utilisateur du frontend pour gérer les animaux et les employés.
- Utilisez les API RESTful exposées par le backend pour effectuer des opérations CRUD.


## Contribuer


Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à soumettre une pull request.


## Licence


Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.


