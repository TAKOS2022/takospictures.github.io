# 🖼️ Dossier — Miniatures (thumbnails)

Place ici les versions compressées/redimensionnées de tes photos
utilisées comme aperçus dans la grille portfolio.

## Convention de nommage

Même nom que l'original avec le suffixe `-thumb` :
```
hiro-concert-thumb.jpg
fjaq-evenement-thumb.jpg
ceo-mae-thumb.jpg
immobilier-thumb.jpg
graduation-thumb.jpg
anniversaire-bonny-thumb.jpg
saint-valentin-thumb.jpg
studio-portraits-thumb.jpg
atelier-creation-contenu-thumb.jpg
```

## Format recommandé
- Largeur : 600px (suffisant pour la grille 4 colonnes)
- Poids : 80–150 Ko max
- Outil gratuit : https://squoosh.app

## Utilisation dans index.html
Remplace le commentaire dans chaque carte portfolio :
```html
<!-- <img src="[URL_THUMB_HIRO]" alt="Artiste Hiro" loading="lazy" /> -->
```
par :
```html
<img src="assets/thumbs/hiro-concert-thumb.jpg" alt="Artiste Hiro" loading="lazy" />
```
