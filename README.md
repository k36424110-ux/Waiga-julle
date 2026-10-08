# Boutique Waiga Julle

## Mettre en ligne (GitHub + Render)
1. GitHub : crée un dépôt (New repository), puis "Add file > Upload files" et envoie TOUT le contenu de ce dossier (index.html, products.js, dossier images).
2. Render : New > Static Site > choisis ton dépôt GitHub.
   - Build Command : laisser vide
   - Publish Directory : `.`
   - Donne un nom au site (ex. waiga-julle) : le lien sera https://waiga-julle.onrender.com

## Ajouter un article
1. Dans GitHub, ouvre le dossier `images` > Add file > Upload files : envoie la photo.
2. Ouvre `products.js` > icône crayon : copie une ligne `{ nom: ..., image: ... },`, colle-la en haut de la liste, change le nom et le chemin de l'image.
3. Commit changes : Render met le site à jour tout seul en 1 à 2 minutes.
