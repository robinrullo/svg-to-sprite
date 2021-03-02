# SVG to Sprite
SVG to Sprite est utilisé pour convertir des fichiers SVG en sprites pour créer des fill-patterns dans Carine

## Attention !
**L'application nécessite une architecture darwin (Linux ou MacOS). Il est impossible de l'utiliser sur Windows**

## Utilisation
* Installez les dépendances

Pour installer les dépendances, lancez
```bash
npm install
```


* Placez vos fichiers SVG dans le dossier icons. Vous pouvez placer ceux dans le dossier icon-exemple si vous n'avez pas de banque d'icon.


* Lancez le script npm "sprite" qui créera les fichiers constituant un sprite.
````bash
npm run sprites
````

* Vous trouverez les couples de fichiers suivants (avec l'option sdf pour changer la couleur de l'icon dans mapbox par la suite) dans le dossier **sprites** :
    1. sprites.json / sprites.png : le sprite 1x
    2. sprites@2x.json / sprites@2x.png : le sprite "retina" 2x (résolution double).
