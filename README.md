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

Utiliser et adapter le code sur cette page : https://masf-html5.blogspot.com/2016/04/html5-orientation-api.html pour faire bouger le logo "HTML5" quand vous bougez le téléphone :

- prendre le code dans la section "Device Motion" (pas device orientation) ; exemple seul ici : http://output.jsbin.com/xupobi
- Créer un nouveau fichier HTML sur votre serveur dans le répertoire `public` et coller le code dedans
- Remarque : il y a une erreur de le code de la balise `<img` -> `<img src="http://...`

## Exercice à faire

Intégrer cet exemple dans la SPA :

- créer une nouvelle vue (section) dans la page HTML
- Rajouter le code HTML de la page dans cette section (ne pas oublier les id des éléments)
- Rajouter le code js dans `client.js`

Si ça ne marche pas : remplacer par des données récupérées d'un des capteurs du téléphone (cf. slide 31 du cours).
