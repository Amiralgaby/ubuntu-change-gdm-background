# ubuntu-change-gdm-background
Il s'agit d'un script qui automatise le processus de mise en place d'une image dans le Gnome Display Manager 
d'Ubuntu afin de modifier son célèbre thème de l'aubergine.

## Disclaimer
Le script 18.04+ a été testé sur Ubuntu 18.04, 18.10, 19.04 et 19,10 seulement et je ne suis pas 
responsable de tout problème qu'il pourrait causer.

Si vous possédez Ubuntu 20.04 et plus, veuillez utiliser le script possédant 20.04+.

## Script Ubuntu 20.04+
### Installation et Usage

I - Copier-coller dans votre éditeur de texte préféré le script ou téléchargez-le.

II - Donnez-lui la possibiliter d'être exécuté  : `chmod +x gdm-change-ubuntu20.04+`. 

III - Lancez-le en tant qu'administrateur avec `sudo ./gdm-change-ubuntu20.04+`.


## Script Ubuntu 18.04+
### Installation et Usage

Tout d'abord, vous devez avoir installé le paquet yad pour pouvoir voir l'interface utilisateur graphique. 
Sur Ubuntu, vous pouvez l'installer avec `sudo apt install yad`.  

I - Copier-coller dans votre éditeur de texte préféré le script ou téléchargez-le.

II - Donnez-lui la possibiliter d'être exécuté  : `chmod +x gdm-change-ubuntu18.04+`. 

III - Lancez-le en tant qu'administrateur avec `sudo ./gdm-change-ubuntu18.04+`.

### Retrouver l'ancien theme 

Vous pouvez restaurer le thème original via la commande `sudo ./gdm-change-ubuntu18.04+ --restore`.

Ce script sauvegarde les images dans le dossier /usr/share/gdm/saved-pictures donc
vous pouvez déplacer l'image d'origine sans perdre les paramètres de l'arrière-plan du gestionnaire de session.
