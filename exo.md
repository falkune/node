# Exercice Pratique (Projet Final)
Description du Projet : Application TodoList

1) Conception de la Base de Données

    - Tables : Utilisateurs, Tâches
    - Champs pour Utilisateurs : id, nom, email, mot_de_passe
    - Champs pour Tâches : id, titre, description, utilisateur_id
2) Fonctionnalités à Implémenter

    - Inscription/Connexion des Utilisateurs
        - Routes : /register, /login
        - Hashage des mots de passe
    - Gestion des Tâches
        - Routes : /tasks (GET), /tasks (POST), /tasks/:id (PUT, DELETE)
        - Vérification de l'authentification avant l'accès aux routes
    - Affichage des Tâches par Utilisateur
        - Afficher uniquement les tâches du utilisateur connecté
3) Étapes de Développement

    - Étape 1 : Conception de la base de données
    - Étape 2 : Création du serveur Express
    - Étape 3 : Implémentation de l'authentification
    - Étape 4 : Implémentation des opérations CRUD pour les tâches
    - Étape 5 : Déploiement de l'application