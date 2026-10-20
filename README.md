# Facila Sendo

    version : 2.00 Octobre 2026
    auteur  : Thierry Le Gall
    contact : facila@gmx.fr
    web     : https://github.com/facila/sendo

 sauvegarde et téléchargement d'équipements réseau fonctionnant en mode running et startup

 sendo utilise facila konekto et sxabloni que vous devez installer
 sendo est utilisé dans facila reto , outil de gestion d'équipements réseau

 sendo.sh : fonction de sauvegarde et de téléchargement d'équipements réseau fonctionnant en mode running et startup

     commande : sendo.sh FUNCTION NAME MARK USER DIRECTORY SOURCE COPY LOGIN ADDRESS USERNAME PASSWORD

     FUNCTION = save  : sauvegarde de la configuration dans l'équipement + puis sur le serveur
     FUNCTION = run   : téléchargement d'une configuration en running + sauvegarde ( save )
     FUNCTION = start : téléchargement d'une configuration en startup
     NAME             : nom de l'équipement
     MARK             : marque de l'équipement
     USER             : utilisateur
     DIRECTORY        : répertoire pour les sauvegardes
     SOURCE           : fichier à télécharger pour run ou start 
     COPY             : mode de copy de l'équipement
     LOGIN ADDRESS USERNAME PASSWORD : paramétres pour kopio.pl et konekto.pl

 sendo_xterm.sh : exécution de sendo.sh dans une fenêtre xterm

     commande   : sendo_xterm.sh "XTERM" FUNCTION NAME PARAMETERS

     XTERM      : paramétres xterm : couleurs , police et taille de la fenêtre
     FUNCTION   : save , run ou start
     NAME       : nom de l'équipement
     PARAMETERS : paramétres pour sendo.sh
