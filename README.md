# pierrerouby-droid.github.io

Site racine du compte. Il sert à deux choses :

- `/.well-known/assetlinks.json` prouve que l’application Android « Chiffres à l’abordage ! » (`io.github.pierrerouby_droid.chiffres`) a le droit d’afficher le jeu en plein écran, sans barre d’adresse ;
- la page d’accueil renvoie vers le jeu : https://pierrerouby-droid.github.io/Chiffres-l-abordage/

Le fichier `.nojekyll` est indispensable : sans lui, GitHub Pages ignore le dossier `.well-known`.
