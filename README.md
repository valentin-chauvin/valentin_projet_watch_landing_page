# A installer sur votre machine

Il suffit de faire ceci la première fois, il n'y a pas besoin de le refaire les fois suivantes.

## Installer NPM
### Sous windows
https://blog.teamtreehouse.com/install-node-js-npm-windows
### Sous mac OS
https://www.dyclassroom.com/howto-mac/how-to-install-nodejs-and-npm-on-mac-using-homebrew

## Installer Git
https://git-scm.com/downloads




# Start a project using HTML and Sass files

## First time

### Créer un repository sur Github
Ne pas créer de .gitignore, récupérer celui fourni par la démo (qui ignore nottament tout le dossier node_modules).

### Pull this repository on your computer (Clone)
Run Github Desktop > Clone a repository

### Run NPM
```bash
cd + chemin_complet_vers_le_dossier_du_site
npm install (création d'un dossier node_modules à la racine du dossier)
```

## Lancement du serveur de développement (npm)
```bash
npm run serve
```
Cela va lancer un serveur de développement sur votre machine (qui doit continuellement touner).
Vous pouvez maintenant lancer l'url `http://localhost:8080` (ou similaire) et votre page s'affichera.

## Modifier le code
Une fois que le serveur est lancé, vous pouvez modifier le contenu du fichier public/index.html
ou src/assets/app.scss et la page se rechargera automatiauement (auto-reload). 

/!\ Si cela ne marche pas rafraîchissez la page dans le navigateur ou relancez entièrement le serveur.
