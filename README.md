# ubuntu-change-gdm-background
Il s'agit d'un script qui change l'arrière-plan du gestionnaire de sessions GDM.
Vous pourrez enfin vous passer du célèbre thème de l'aubergine (violet uni).

## Disclaimer
Le script 18.04 n'est plus maintenu, il a fonctionné pour une Ubuntu 18.04

Si vous possédez Ubuntu 20.04 et plus, veuillez utiliser le script possédant 20.04+.

## Script Ubuntu 20.04
### Installation et Usage

I - Copier-coller dans votre éditeur de texte préféré le script ou téléchargez-le.

II - Donnez-lui la possibilité d'être exécuté  : `chmod +x gdm-change-ubuntu20.04`. 

III - Lancez-le en tant qu'administrateur avec `sudo ./gdm-change-ubuntu20.04`.

Optionnelement vous pouvez [cacher le filigrane "Ubuntu"](https://askubuntu.com/questions/1150894/how-to-remove-change-ubuntu-logo-in-the-loging-page-ubuntu-19-04) sur l'écran de connexion avec l'option
`--cache-filigrane`
il suffit donc le rajouter à la commande :
`sudo ./gdm-change-ubuntu20.04 --cache-filigrane`

## Script Ubuntu 18.04
### Installation et Usage

Tout d'abord, vous devez avoir installé le paquet yad pour pouvoir voir l'interface utilisateur graphique. 
Sur Ubuntu, vous pouvez l'installer avec `sudo apt install yad`.

I - Copier-coller dans votre éditeur de texte préféré le script ou téléchargez-le.

II - Donnez-lui la possibilité d'être exécuté  : `chmod +x gdm-change-ubuntu18.04`. 

III - Lancez-le en tant qu'administrateur avec `sudo ./gdm-change-ubuntu18.04`.

### Retrouver l'ancien thème 

Vous pouvez restaurer le thème original via l'option `--restore` sur tout les scripts.

### Bug : le gestionnaire n'ouvre pas la session même si le mot de passe est correct
Des posts sur des forums explique le même problème, pour résoudre le bug je vous invite à les regarder.

À tester si le gestionnaire de session boucle sur la page de login : personnellement, j'ai mis un mauvais mot de passe puis le bon et ça fonctionne à nouveau.
