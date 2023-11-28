# Application de Localisation des Pharmacies


## À propos du Projet
Ce projet vise à développer une application qui facilite la localisation des pharmacies dans une ville ou une zone spécifique. 
Elle offre des fonctionnalités telles que la recherche de pharmacies par ville ou zone, le filtrage selon les horaires de garde, et plus encore.


## Fonctionnalités
  **Recherche des pharmacies** : Par ville ou zone.
  **Filtrage des pharmacies** : Selon les horaires de garde (jour/nuit).
  **Affichage de la liste** : Liste des pharmacies trouvées.
  **Informations détaillées** : Affichage des détails pour chaque pharmacie.
  **Pharmacies favorites** : Marquer certaines pharmacies en tant que favorites.
  **Gestion des erreurs** : Affichage de messages d’erreur clairs.

## Contraintes Techniques
  **Backend** : Développé avec Spring Boot.
  **Base de données** : Utilisation d’une base de données relationnelle mysql.
  **Géolocalisatio**n : Intégration de  Maps pour le calcul d’itinéraire et la localisation.
  **Frontend** : Implémentation avec React.js (web) .

## Comment Commencer
Pour lancer le projet localement, suivez les étapes suivantes :

# Clonez le dépôt
git clone https://github.com/chaourad/localisation-pharmacie.git

# Installez les dépendances
# Backend
cd backend
./mvnw install

# Frontend
cd frontend
npm install

# Lancez l'application
# Backend
./mvnw spring-boot:run

# Frontend
npm start


