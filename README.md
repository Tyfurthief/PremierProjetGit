# Introduction à GIT

## Concept

Gérer l'historique des versions.

## Utilisation

- Initialiser un dépôt local à la racine du projet : `git init`
- Mettre des fichiers en indésirable/à ignorer comme : Les données confidentielles (ex : les fichiers d'environnement .env), les modules (ex : node_modules), les artefacts de construction (ex : .build), les logs d'erreur, avec la commande : `.gitignore`

## Synchronisation client-server

- Pousser du dépôt local vers le serveur : `git push`
- Recevoir du serveur vers le dépôt local : `git pull`
- Copie du serveur vers le local : `git clone`
 
## Notion de branche de travail
- Changer de branche : `git checkout -b`
- Afficher les branches existantes : `git branch` ou `git status`