# Exercice 5 - Partionnement

## Objectifs :
Cet exercice a pour objectifs : 
* d'utiliser une table partitionner
* de partitionner une nouvelle table

## Utiliser la table payments

* Dans le schéma fourni la table payment est déjà partitionné et une nouvelle table est créé pour chaque mois.
* Quel est le type de partitionnement utilisé par cette table ? 
* Que se passe t'il si vous ajouter un payment sur cette table ? 

## Déclarer une nouvelle table de partitionnement

* La table rental contient l'ensemble des locations effectuées.
* Celle-ci croit toutes les semaines et atteint aujourd'hui plusieurs milliers de lignes. 
* Quel type de partitionnement peut être mis en place pour cette table ?
* Comment mettre en place le partitionnement sur cette table ? (requête de création / modification des tables)
* Une fois la table partitionné tester une requête en lecture et une en écriture sur cette table pour voir l'impact sur les performances.