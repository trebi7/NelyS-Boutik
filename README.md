# Nely'S Boutik — Archive statique du site Wix

Ce dépôt contient une archive statique (HTML + CSS) du contenu du site Wix
**Nely'S Boutik**, dont l'original se trouve à l'adresse :
https://nelysboutik.wixsite.com/monsite-1

## À propos de cette archive

Wix ne permet pas d'exporter le "code source" éditable d'un site (il n'y a pas
de fichiers HTML/CSS/JS lisibles à télécharger depuis l'éditeur Wix : le site
est généré dynamiquement par leur plateforme). Ce dépôt est donc une
**reconstruction statique** du contenu réel du site (textes, prix, produits,
navigation, mentions de contact) sous forme de pages HTML simples et propres,
plutôt qu'une copie brute du code généré par Wix.

Contenu couvert :

- Accueil (`index.html`)
- Boutique (`boutique.html`)
- Vêtements (`vetements.html`)
- Parfumerie (`parfumerie.html`)
- Sacs à main (`sacs-a-main.html`)
- Chaussures (`chaussures.html`)
- Arrivages (`arrivages.html`)
- Vêtements Hommes (`vetements-hommes.html`)
- Pages légales (mentions légales, cookies, confidentialité, conditions
  d'utilisation) — ce sont les modèles par défaut de Wix, non personnalisés
  sur le site d'origine au moment de l'archivage.

## Limites connues

- Les images restent hébergées sur le CDN de Wix (`static.wixstatic.com`) et
  sont simplement référencées par leur URL d'origine ; elles ne sont pas
  copiées dans ce dépôt. Si Wix supprime ces fichiers, les images cesseront
  de s'afficher.
- Certaines pages catégories (Boutique, Vêtements, Arrivages) affichaient un
  bouton « Voir plus » sur le site d'origine : d'autres produits peuvent donc
  exister au-delà de ce qui a été capturé ici.
- Il n'y a pas de panier ni de paiement fonctionnel : ce n'est pas une
  boutique en ligne opérationnelle, seulement une archive de présentation.

## Utilisation

Ces fichiers forment un site statique classique : ouvrez simplement
`index.html` dans un navigateur, ou déployez le dossier tel quel sur
GitHub Pages, Netlify, Vercel, etc.

Généré le 2026-09-27 à partir du contenu visible sur
https://nelysboutik.wixsite.com/monsite-1
