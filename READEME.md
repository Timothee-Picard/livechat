# Livechat

Ce projet est un live chat développé en Node.js utilisant des websockets pour la communication en temps réel.
## Prérequis

- Node.js (version 12 ou supérieure)
- npm (gestionnaire de paquets Node.js)

## Installation

1. Clonez ce dépôt sur votre machine locale :

    ```sh
    git clone
    cd livechat
    ```
2. Installez les dépendances nécessaires :

    ```sh
    npm install
    ```
## Utilisation en Développement

1. Démarrez votre serveur Node.js :

    ```sh
    npm start
    ```
   
2. Ouvrez votre navigateur et accédez à l'adresse `http://localhost:8080`.
3. Ouvrez plusieurs onglets pour simuler plusieurs utilisateurs et discuter en temps réel.
4. Pour arrêter le serveur, appuyez sur `Ctrl + C`.
5. Pour redémarrer le serveur automatiquement à chaque modification, utilisez `nodemon` :

    ```sh
    npm run dev
    ```
## Structure du Projet
    
    ```plaintext
    .
    ├── public
    │   ├── index.html
    ├── server.js
    ├── package.json
    └── package-lock.json
    ```