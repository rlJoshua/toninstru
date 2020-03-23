# TonInstru
Site permettant aux musiciens de vendre ou d'acheter de instruments.

Il a été réalisé avec :
- HTML/CSS
- PHP - Symfony 5
- JQuery
- Bootstrap

## Installation
- Cloner le projet en ssh

- Créer une une base de donnée **toninstru** et insérer le script dans la donnée

- Executer la commande suivante :  
    'cp .env-example .env'  
et configurer le fichier .env

- Mettre à jour la base de donnée  
    'php bin/console make:migration'  
    'php bin/console doctrine:migration:migrate'
    
- Mettre à jour le composer  
    'composer update'
    
- Lancer le projet  
    'symfony server:start -d'
    

## Instructions

Pour le git, la branche **dev** à été créer pour servir de préproduction. 
Dans ce cas toute les branches doivent partir de la branche **dev** et les merge requests 
doivent être en destination de cette branche.


S'il a des soucis n'hésitez pas à me contacter.