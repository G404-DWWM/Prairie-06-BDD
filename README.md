# Prairie-06-BDD

## Les Bases De Données





## 📽️ Présentation :

Présentation [Les bases de données](https://docs.google.com/presentation/d/1PJjghVAjdIgHL4rzNCNJpWE9oTDSM2Kdby6Mvc8JsJI/edit#slide=id.g3d514b032d_0_5)

Présentation [Docker et Devilbox](https://docs.google.com/presentation/d/1plRYFnmrsp0QNPWqatKqsWDoC3zZIjgDr0JgXN4oGNc/edit?usp=sharing)




# 👨‍💻 Installer un environnement de développement

Pour travailler sur une base de données, il va falloir installer un environnement de développement. 


* Pour Windows → installation de **laragon** puis de **phpmyadmin**


* Pour linux → installation de **docker** puis de **devilbox**. 

L'objectif est de réussir à ouvrir cette page : https://www.cloudways.com/blog/wp-content/uploads/phpMyAdmin-dashboard-1024x524.png  




    
Pour y arriver il vous faudra faire des recherches en anglais et vous entraider pour la compréhension des astuces trouvées.  
 
[Documentation Installation Docker](https://docs.docker.com/engine/install/ubuntu/) 


Install Docker Engine : 3 commandes principales à effectuer


[Documentation Installation Docker compose](https://docs.docker.com/compose/install/linux/)


Install the Compose plugin : 3 commandes principales à effectuer


    
[Documentation Installation Devilbox](https://devilbox.readthedocs.io/en/latest/getting-started/install-the-devilbox.html#download-the-devilbox)


En suivant la documentation : 2 commandes principales à effectuer : git clone le repo devilbox, se placer dans le dossier et créer le .env


<ins>Puis lancer l’environnement local avec la commande :</ins> sudo docker compose up 


**⚠️	 Tout le monde doit avoir réussi cette étape avant de passer à la suite.**


    


# 📃Ressources & Documentation :

Avant de commencer les exercices, voici quelques petits cours et tutoriels pour approfondir le sujet:  

 - [ Introduction au langage SQL | Développement Informatique](https://developpement-informatique.com/article/278/introduction-au-langage-sql) 
 - [Concevoir une base de données](https://colibri.unistra.fr/fr/course/list/concevoir-une-base-de-donnees)
 - [Notion de base en SQL cours + exercices](https://colibri.unistra.fr/fr/course/list/concevoir-une-base-de-donnees)


 - [Cours et Tutoriels sur le Langage SQL - Documentation officiel](https://sql.sh/)


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Exercices Les Bases De Données


## 👪️Exercice de groupe

Pour comprendre SQL vous allez imaginer la BDD du centre de formation.

Ensuite avec les connaissances acquises, vous allez imaginer le **schéma** de cette BDD :



* Combien de tables créer ?
* Quelles colonnes dans ces tables ?
* Quel type de données ?
* Quelles relations peut-il y avoir entre les différentes tables ? 

 
Une fois ce schéma réalisé (sur [draw.io](https://app.diagrams.net/) ou [drawSQL](https://drawsql.app) par exemple) vous allez créer cette BDD dans PhpMyAdmin en utilisant uniquement des commandes SQL !  
 

## 🤷Exercice individuel ou en groupe

Un cours sur le langage SQL n’est vraiment utile que si on essaye de le mettre en pratique dans un contexte d’usage réel.

### Prérequis

Télécharger les bases de données d’exemples, qui seront utilisées au sein des exercices.

Pour cela créez une base de données et ajoutez ces 2 tables :


* Table “[villes de France](https://sql.sh/ressources/sql-villes-france/villes_france.sql)” (8.4Mo)
* Table “[départements de France](https://sql.sh/ressources/sql-departement-france/departement.sql)” (7.9Ko)

_Astuces : gardez une sauvegarde de ces tables avant d’effectuer les exercices._

**Le but de cette exercice est de trouver les requêtes SQL permettant d’effectuer chacune des demandes suivantes :**



1. Obtenir la liste des 10 villes les plus peuplées en 2012
2. Obtenir la liste des 50 villes ayant la plus faible superficie
3. Obtenir la liste des départements d’outres-mer, c’est-à-dire ceux dont le numéro de département commencent par “97”
4. Obtenir le nom des 10 villes les plus peuplées en 2012, ainsi que le nom du département associé
5. Obtenir la liste du nom de chaque département, associé à son code et du nombre de commune au sein de ces département, en triant afin d’obtenir en priorité les départements qui possèdent le plus de communes
6. Obtenir la liste des 10 plus grands départements, en terme de superficie
7. Compter le nombre de villes dont le nom commence par “Saint”
8. Obtenir la liste des villes qui ont un nom existants plusieurs fois, et trier afin d’obtenir en premier celles dont le nom est le plus souvent utilisé par plusieurs communes
9. Obtenir en une seule requête SQL la liste des villes dont la superficie est supérieur à la superficie moyenne
10. Obtenir la liste des départements qui possèdent plus de 2 millions d’habitants
11. Remplacez les tirets par un espace vide, pour toutes les villes commençant par “SAINT-” (dans la colonne qui contient les noms en majuscule)


# 🏆️ Objectifs



* j'ai compris l'utilité d'une base de données
* je sais utiliser les commandes de base de SQL

