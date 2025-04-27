Gestion de Clients - Application Electron.js
Présentation
Gestion de Clients est une application de bureau développée avec Electron.js, permettant de répertorier, modifier et gérer des informations clients dans une base de données locale connectée via WAMP et phpMyAdmin.

Cette solution est idéale pour les petites entreprises souhaitant une gestion simplifiée de leur base client sans dépendance à des services externes.

Technologies utilisées
Electron.js : Création de l’application de bureau multiplateforme.

Node.js : Pour la communication entre l’interface et la base de données.

PHP : Scripts côté serveur pour gérer les requêtes vers MySQL.

MySQL : Base de données pour stocker les informations clients.

WAMP : Serveur local pour exécuter PHP et MySQL.

HTML / CSS / JavaScript : Interface utilisateur de l’application.

Fonctionnalités principales
Ajout de clients : formulaire simple pour enregistrer un nouveau client dans la base de données.

Modification des informations : possibilité d’éditer les informations existantes.

Suppression de clients : supprimer un client de la base en un clic.

Affichage dynamique : liste des clients actualisée en temps réel.

Connexion sécurisée : pour accéder à la base et limiter les accès.

Installation et Lancement
Installer WAMP et démarrer le serveur local (Apache + MySQL).

Configurer la base de données :

Créer une base dans phpMyAdmin (ex : clients_db).

Importer le fichier .sql fourni (structure de la table clients).

Cloner ou télécharger le projet sur votre machine.

Installer les dépendances Node.js :

npm install
Lancer l'application Electron :

npm start

Sécurité
Validation côté serveur et client des champs de formulaire.

Protection contre les injections SQL via requêtes préparées en PHP.

Connexions locales sécurisées (pas d'accès distant).

Résultats attendus
Une application rapide et légère pour la gestion client locale.

Une interface utilisateur claire et intuitive.

Une base de données facilement exploitable et sauvegardable via phpMyAdmin.
