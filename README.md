# electricien_app

Plateforme dédiée aux électriciens, permettant à ces derniers de gérer leur compte, afficher leurs informations et profiter d'une interface intuitive pour administrer leur profil. Ce projet combine les technologies modernes de développement **Vue.js** pour le front-end et **Laravel** pour le back-end, avec une architecture client-serveur où l'API Laravel alimente l'interface Vue.js.

## Fonctionnalités principales
- **Gestion de compte** : inscription, connexion et modification des informations personnelles.
- **Onboarding** : collection d'informations supplémentaires lors de l'inscription.
- **Tableau de bord** : affichage des informations de l’électricien inscrit avec des fonctionnalités de gestion de compte.
  
## Technologies utilisées
- **Front-end** : 
  - Vue.js
  - Vue Router
  - Axios pour les requêtes API
- **Back-end** :
  - Laravel 10 (API RESTful)
  - Laravel Sanctum pour l'authentification sécurisée
  - Base de données relationnelle (MySQL)

## Installation
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/moussaouinour/electricien_app.git
2. Installez les dépendances
   ###### Frontend
    ```bash
    cd electricien-frontend
    npm install
    
     Back-end :
    ``bash
    cd api_electricien
    composer install
    
4. Configurez le fichier .env et les paramètres de la base de données.
   ###### Frontend
   ```bash
   npm run serve
   
   
     ###### Frontend
   ```bash
   php artisan serve

   
