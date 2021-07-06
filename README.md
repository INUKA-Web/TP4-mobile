# TP4-mobile

## URL du cours

Web mobile : https://perso.liris.cnrs.fr/lionel.medini/enseignement/M1IF13/revealJS/#cm4-mobile

## Vérifications

On va vérifier que votre téléphone peut se connecter au serveur sur voter ordinateur par le wifi :

- ouvrir Powershell et taper `ipconfig` -> récupérer l'adresse IPV4
- lancer le serveur sur votre ordinateur
- Ouvrir la page à http://localhost:3000/ sur votre ordinateur
- Remplacer "localhost" par l'adresse IP sur votre ordinateur -> noter cette adresse
- Connecter votre téléhone **sur la même borne wifi que l'ordinateur**
- ouvrir la même adresse

Une fois que vous arrivez à accéder à votre site depuis votre téléphone :

## Vibration API

- Recopier cette instruction : `navigator.vibrate([50, 100, 150]);` (source : https://www.w3.org/TR/vibration/#examples)
- La rajouter dans le code de la fonction de callback qui affiche l'heure.

## Device Motion API

Utiliser et adapter le code sur cette page : https://masf-html5.blogspot.com/2016/04/html5-orientation-api.html pour faire bouger le logo "HTML5" quand vous bougez le téléphone.
