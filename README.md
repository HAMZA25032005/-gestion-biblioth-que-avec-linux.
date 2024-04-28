# Gestion des comptes et sauvegardes
Ce projet vise à simplifier la gestion des utilisateurs et des sauvegardes sur un serveur Unix en automatisant les tâches courantes de l'administrateur système. Il consiste en la création d'un script shell qui permettra de gérer efficacement les comptes utilisateurs, les groupes, ainsi que les sauvegardes des répertoires.
Le script de gestion des utilisateurs et des sauvegardes offre les fonctionnalités suivantes :

-Gestion des utilisateurs et des groupes : Ajout, liste et suppression d'utilisateurs et de groupes. Prise en charge de l'ajout en masse de groupes à partir d'un fichier CSV, ainsi que la suppression en masse d'utilisateurs depuis un fichier CSV. Gestion des erreurs telles que les doublons et les fichiers CSV mal formatés.
-Gestion des archives : Archivage de répertoires individuels ou groupés avec suppression automatique des originaux. Prise en charge de l'archivage manuel ou à partir d'un fichier texte. Gestion des erreurs comme les répertoires inexistants et les fichiers texte mal formatés.
-Menu de navigation : Interface interactive permettant aux utilisateurs de sélectionner facilement les opérations à effectuer, offrant une expérience conviviale.
-Traçabilité des opérations : Enregistrement de toutes les actions et erreurs dans deux fichiers journaux distincts, GestionUser.log et Archivage.log, pour faciliter la gestion et la résolution des problèmes.
