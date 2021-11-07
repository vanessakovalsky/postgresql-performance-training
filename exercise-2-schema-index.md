# Exercice 2 - Optimiser le schéma et les index 

## Objectifs
Cet exercice a pour objectifs : 
* d'optimiser le schéma de la base de données
* de vérifier si les index positionnés suffisent ?

## Optimiser le schéma de la base de données
* A l'aide d'adminer, définir quels sont les tables présentes et les liens entre ces tables ?
* Quels sont les types de données utilisés ?
* Certaines données sont t'elle répetées dans différentes tables ?
* Pour les usages suivants, dans quels tables va t'on chercher les données : 
    * Obtenir la liste des films trié par acteurs
    * Obtenir le montant total (somme) des locations par mois
    * Obtenir la liste des films loués par les clients habitant dans le district du Texas
* Vous obtenez alors des requêtes qui sont celles utilisées dans les applications qui s'appuient sur cette base et vont servir à comparer et optimiser les performances de notre base de données.

## Optimiser les index
* Quels sont les index déjà présents sur la BDD ?
* De quel type sont t'ils ?
* Peut t'on ajouter d'autres index ?  
/!\ Pensez à utiliser la commande EXPLAIN et son option ANALYZE avec nos requêtes de l'étape précédente pour tester si des index sont utilisés et si en rajouter change quelque chose 
