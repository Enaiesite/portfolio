# Portfolio — Énaï Léveillé

Portfolio professionnel multi-pages (HTML / CSS), prêt pour GitHub Pages.
Chaque page est **autonome** : le style et le script sont intégrés, il n'y a
rien d'autre à installer.

## Fichiers
- `index.html` — Accueil
- `parcours.html` — Expériences et formations
- `competences.html` — Compétences, langues et centres d'intérêt
- `contact.html` — Coordonnées
- `photo.jpg` — la photo de profil (à ajouter, voir plus bas)

## Mise en ligne (GitHub Pages)
1. Crée un dépôt public (par ex. `portfolio`).
2. Ajoute les 4 fichiers `.html` et la `photo.jpg` à la racine du dépôt.
3. Va dans **Settings → Pages**, choisis la branche `main` et le dossier
   `/ (root)`, puis **Save**.
4. Après ~1 minute, le site est en ligne à l'adresse affichée sur cette page.

> Astuce : pour une adresse « propre » du type `enai-leveille.github.io`,
> nomme le dépôt exactement `enai-leveille.github.io`.

## Personnaliser
- **Photo** : place un fichier nommé `photo.jpg` à la racine (format portrait
  conseillé, ratio ~4:5). Pour un autre nom, modifie `src="photo.jpg"` dans
  `index.html`.
- **Couleurs** : en haut du bloc `<style>` de chaque page, dans `:root`
  (`--paper`, `--accent`, `--ink`…). L'accent actuel est un caramel chaud
  `#A96A2C`.
- **Polices** : Fraunces (titres) et Plus Jakarta Sans (texte), chargées depuis
  Google Fonts. Les icônes viennent de Font Awesome. Elles s'affichent dès que
  la page est ouverte avec une connexion internet (donc une fois en ligne).
- **LinkedIn** : pour l'ajouter dans le pied de page, insère dans le bloc
  `<nav class="foot-links">` :
  `<a href="https://www.linkedin.com/in/ton-profil" target="_blank" rel="noopener">LinkedIn</a>`
- **CV téléchargeable** : place un `cv.pdf` à la racine et ajoute un bouton sur
  la page d'accueil, à côté des autres :
  `<a class="btn btn-ghost" href="cv.pdf" target="_blank" rel="noopener">Télécharger mon CV</a>`

## Deux détails à vérifier
- L'orthographe du prénom est harmonisée en **« Énaï »** (avec accent) partout ;
  remplace-la si besoin.
- Le contenu (expériences, compétences, coordonnées) reprend fidèlement ta
  version : vérifie simplement l'adresse e-mail et le numéro de téléphone.
