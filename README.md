BookMania
BookMania est une application de gestion de bibliothèque conçue pour aider les bibliothèques de petite et moyenne taille à organiser leurs collections de livres, gérer les emprunts, et suivre les retours de manière efficace.

Fonctionnalités
Gestion des livres : Ajout, modification et suppression des informations des livres (titre, auteur, année de publication, genre, etc.).
Suivi des emprunts : Gestion des emprunts de livres par les utilisateurs avec des dates de retour prévues.
Notifications : Rappels automatiques pour les retours de livres en retard.
Recherche avancée : Recherche par titre, auteur, genre, ou autres critères.
Rapports : Génération de rapports sur les emprunts et les retours.
Installation
Prérequis
Node.js
npm
MySQL ou autre base de données compatible
Étapes
Clonez le dépôt :

sh
Copier le code
git clone https://github.com/votre-utilisateur/bookmania.git
cd bookmania
Installez les dépendances :

sh
Copier le code
npm install
Configurez la base de données :

Créez un fichier .env à la racine du projet et ajoutez-y les informations de configuration de la base de données.
Exemple de fichier .env :
makefile
Copier le code
DB_HOST=localhost
DB_USER=root
DB_PASS=password
DB_NAME=bookmania
Démarrez l'application :

sh
Copier le code
npm start
Utilisation
Ouvrez votre navigateur et rendez-vous sur http://localhost:3000.
Créez un compte administrateur.
Commencez à ajouter des livres et gérez les emprunts et les retours.
Contribution
Les contributions sont les bienvenues ! Veuillez suivre les étapes suivantes pour contribuer :

Forkez le dépôt.
Créez une branche pour votre fonctionnalité ou correction de bug :
sh
Copier le code
git checkout -b feature/nom-de-la-fonctionnalité
Faites vos modifications et commitez-les :
sh
Copier le code
git commit -m "Description de la fonctionnalité ajoutée"
Poussez vers votre dépôt forké :
sh
Copier le code
git push origin feature/nom-de-la-fonctionnalité
Ouvrez une Pull Request sur le dépôt original.
Licence
Ce projet est sous licence MIT. Veuillez consulter le fichier LICENSE pour plus de détails.
