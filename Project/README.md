# PROJET SGBD - GESTION DE FLOTTE DE VELOS ECLECTRIQUES

Author : Coralie DEPLANNE, Yves LEBARBIER, Quentin PAUWELS
Year : 2021

##DESCRIPTION

Ce projet de SGBD est un projet proposé par l'ENSEIRB MATMECA
afin de mettre en application les éléments vus en cours de SGBD.
Ce projet s'est déroulé durant 3 semaines par équipe de 3.

## SUR INTERNET

Pour accèder à la BDD avec une interface dynamique, veuillez vous rendre
sur :

## INSTALLATION

Pour le projet, le SGBD choisi est MySQL.
 
Afin de créer la base de données, veuillez exécutez dans l'ordre les scripts :
```mysql
> source creation.sql
> source peuplement.sql
> source creation_other.sql
```

Une base de données au nom de PROJECT_SQL s'est ainsi créée.
C'est cette dernière qu'il faut utiliser à l'aide de la commande :
```mysql
> use PROJECT_SQL
```

Afin de supprimer la BDD il faut exécuter dans l'ordre les scripts :
```mysql
> source suppression.sql
> source suppression_other.sql
```

Ou sinon un script suppression_all.sql permet de réaliser cette même tâche


## UTILISATION

Si l'utilisation se fait via le terminal, la liste des requêtes de consultations
sont visibles dans un fichier consultation.sql OU consultations_admin.sql, en fonction
du type de consultations recherchés.

Il est important de savoir qu'il ne faut pas lancer ces 2 fichiers .sql car ces derniers
contiennent des CALL sans valeur renseignées, ceux qui provoqueraient logiquement des
erreurs.