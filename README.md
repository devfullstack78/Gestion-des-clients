Gestion de Clients - Application Electron.js
Présentation
Gestion de Clients est une application de bureau développée avec Electron.js, permettant de répertorier, modifier et gérer des informations clients dans une base de données locale connectée via WAMP et phpMyAdmin.

Cette solution est idéale pour les petites entreprises souhaitant une gestion simplifiée de leur base client sans dépendance à des services externes.

Technologies utilisées
Electron.js : Création de l’application de bureau multiplateforme.

Node.js : Communication entre l’interface et le serveur local.

PHP : Traitement des requêtes entre l'application et la base MySQL.

MySQL : Stockage structuré des données clients.

WAMP : Serveur local pour exécuter PHP et MySQL.

HTML / CSS / JavaScript : Interface graphique de l'application.

Fonctionnalités principales
Ajout de clients : via un formulaire.

Modification : possibilité de mettre à jour les informations client.

Suppression : gestion et suppression de fiches client.

Affichage en temps réel : liste mise à jour sans rechargement.

Connexion sécurisée : pour éviter tout accès non autorisé.

Structure du projet
graphql
Copier
Modifier
/GestionClients
│
├── /src
│   ├── index.html       # Interface principale
│   ├── style.css        # Feuilles de styles
│   ├── main.js          # Lancement de la fenêtre Electron
│   └── renderer.js      # Logique de l’interface utilisateur
│
├── /php
│   ├── addClient.php    # Script PHP pour ajouter un client
│   ├── updateClient.php # Script PHP pour modifier un client
│   ├── deleteClient.php # Script PHP pour supprimer un client
│   └── getClients.php   # Script PHP pour récupérer la liste
│
├── /database
│   └── clients_db.sql   # Fichier SQL pour créer la base de données
│
├── package.json         # Configuration Electron et dépendances Node
├── README.md            # Fichier de documentation (ce fichier)
└── .gitignore           # Fichiers à ignorer par Git
Installation et Lancement
Installer WAMP et démarrer Apache + MySQL.

Créer une base de données clients_db dans phpMyAdmin.

Importer le fichier /database/clients_db.sql pour créer les tables.

Cloner ou télécharger le projet.

Validation des champs en JavaScript et PHP.

Application accessible uniquement en local.

Résultats attendus
Gestion rapide et fiable des fiches clients.

Interface claire et facile à utiliser.

Aucune dépendance à un service externe, tout reste local.

✨ Projet développé par devfullstack78
