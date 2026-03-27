# 🎬 Dossier — Vidéos

Place ici tes vidéos promotionnelles et événementielles.

## Convention de nommage recommandée

```
fjaq-evenement.mp4
immobilier.mp4
graduation.mp4
atelier-creation-contenu.mp4
```

## Format recommandé
- Extension : `.mp4` (H.264, compatible tous navigateurs)
- Résolution max : 1080p
- Poids max : 50 Mo par vidéo

## ⚠️ Attention GitHub Pages
GitHub Pages a une limite de 100 Mo par fichier et recommande de garder
le repo sous 1 Go. Pour les vidéos lourdes, préfère Cloudinary (gratuit
jusqu'à 25 Go) et utilise l'URL directement dans index.html.

## Utilisation dans index.html (vidéo locale)
```html
data-type="video"
data-media="assets/videos/fjaq-evenement.mp4"
```

## Utilisation dans index.html (Cloudinary)
```html
data-type="video"
data-media="https://res.cloudinary.com/TON_ID/video/upload/fjaq-evenement.mp4"
```
