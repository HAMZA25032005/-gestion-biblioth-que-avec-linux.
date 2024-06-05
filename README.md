# Gestion des Comptes Utilisateurs et des Sauvegardes 👨🏻‍💻👨🏻‍🎓📋

## Introduction

Ce projet a pour objectif de développer un script permettant de gérer les comptes utilisateurs et leurs répertoires sur un serveur Unix. Le script encapsule différentes opérations administratives pour simplifier la gestion et éviter les erreurs courantes. Il offre des fonctionnalités pour gérer les utilisateurs et les groupes ainsi que pour archiver les répertoires.

## Spécifications Fonctionnelles

### Gestion des Utilisateurs et des Groupes
Le script permet à l'administrateur de :
- Ajouter un utilisateur avec un login, un mot de passe et un groupe.
- Ajouter un groupe d'utilisateurs à partir d'un fichier CSV.
- Créer un groupe.
- Lister les utilisateurs avec leur login et groupe.
- Supprimer un utilisateur par login.
- Supprimer un groupe et tous ses utilisateurs.
- Supprimer un ensemble d'utilisateurs à partir d'un fichier CSV.

#### Erreurs Gérées
- Utilisateur déjà existant ou groupe non existant.
- Fichier CSV non existant ou mal formaté.
- Information erronée dans un fichier CSV.
- Suppression d'un utilisateur ou groupe non existant.

### Gestion des Archives
Le script permet d'archiver des répertoires d'utilisateurs :
- Archiver un répertoire.
- Archiver un ensemble de répertoires.
- Archiver un ensemble de répertoires à partir d'un fichier texte.

#### Erreurs Gérées
- Répertoire non existant.
- Fichier texte non existant ou mal formaté.
- Information erronée dans le fichier texte.

### Traçabilité des Opérations
Toutes les opérations et erreurs sont enregistrées dans deux fichiers log :
- `GestionUser.log`
- `Archivage.log`

  ### Menu de Navigation
Le script propose un menu de navigation permettant d'accéder à toutes les opérations mentionnées.

![image](https://github.com/HAMZA25032005/Gestion-des-comptes-et-sauvegardes/assets/143803507/a38c74ac-e24e-45af-8523-5c37f8d005da) 

### La Gestion Des Utilisateurs ET Des Groupes
![image](https://github.com/HAMZA25032005/Gestion-des-comptes-et-sauvegardes/assets/143803507/702b3ea2-45b5-4ae4-b007-efc610e824a2)

### La Gestion Des Archives
![image](https://github.com/HAMZA25032005/Gestion-des-comptes-et-sauvegardes/assets/143803507/eb5e22aa-a5c1-4349-bf9b-c9d8b5ab05a8)







