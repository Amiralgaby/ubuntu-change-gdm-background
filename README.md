# ubuntu-change-gdm-background 
Il s'agit d'un script qui automatise le processus de mise en place d'une image dans le Gnome Display Manager 
d'Ubuntu afin de modifier son célèbre thème de l'aubergine (vraiment pas ouf).

## Disclaimer
Ce script a été testé en Ubuntu 18.04, 18.10, 19.04 et 19,10 seulement et je ne suis pas 
responsable de tout problème qu'il pourrait causer.
CE SCRIPT NE FONCTIONNERA PAS AVEC LA NOUVELLE DISTRIBUTION UBUNTU 20.04. Si vous voulez changer Ubuntu
20.04 gdm backgroud image, vous devez utiliser un autre script disponible à 
https://github.com/thiggy01/ubuntu-20.04-change-gdm-background.

## Installation and Usage 

Tout d'abord, vous devez avoir installé le paquet yad pour pouvoir voir l'interface utilisateur graphique. 
Sur Ubuntu, vous pouvez l'installer avec `sudo apt install yad`.  

I - Copier-coller dans votre éditeur de texte préféré.

II - Donnez-lui la possibiliter d'être exécuté  : `chmod +x ubuntu-change-gdm-background`. 

III - Lancez-le en tant qu'administrateur avec `sudo ./ubuntu-change-gdm-background`.

## Retrouver l'ancien theme 

Vous pouvez restaurer le thème original via la commande `sudo ./ubuntu-change-gdm-background --restore`.

Ce script sauvegarde les images dans le dossier /usr/share/gdm/saved-pictures donc
vous pouvez déplacer l'image d'origine sans perdre les paramètres de l'arrière-plan du gestionnaire de session.
