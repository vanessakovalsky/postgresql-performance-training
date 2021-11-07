# Exercice 1 - Installation de l'environnement et amélioration du paramètrage

## Objectifs :
Cet exercice a pour objectifs : 
* de vous faire installer un environnement de travail
* de vérifier les ressources à disposition
* d'optmiser le paramètrage de PostgreSQL pour améliorer les performances

## Pré-requis : 

* Avoir docker installé sur son poste : https://www.docker.com/get-started
* Avoir docker-compose installé : https://docs.docker.com/compose/install/ 
* Avoir accès à internet et au hub docker : https://hub.docker.com/ 

## Installation de l'environnement

* Cloner se dépôt et positionner vous dans le dossier sql
* Lancer un démarrage des conteneurs avec docker-compose :
```
docker-compose up -d
```
* Accéder à l'interface d'administration Adminer sur http://localhost:8080 
* Explorer la base de données importée. 
* Celle-ci contient des données sur des films et va nous permettre de travailler tout au long des différents exercices.

## Quels sont les ressources à disposition ?

* Y'a t'il des limites de ressources (CPU, RAM, stockage) de définit sur le conteneur ?
* Quels sont les ressources utilisées par le conteneur ? 
* Comment surveiller / optimiser les ressources disponibles ?

## Paramètrage 

* Connecter vous dans le conteneur et identifier le fichier de configuration utilisé ?
* Quels sont les paramètres en place pour les différents tampons ?
* Quel est le nombre max de connections ?
* Quelle est la taille du cache ?

