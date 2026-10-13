# Page_perso_HTML

Page web personnelle réalisée en HTML et CSS pendant l'été de préparation à la formation CDA (Concepteur Développeur d'Applications).

Le site présente Benjamin : sa photo, ses formations, son parcours professionnel, ses qualités et ses prochaines échéances.

## Aperçu

La page est composée de :

- un titre et une barre de navigation avec des liens d'ancrage vers chaque section ;
- une photo ;
- quatre sections : **Formations**, **Parcours professionnel**, **Qualités**, **Échéances à venir** ;
- un pied de page.

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | Page principale du site (« Page web n°2 de Benjamin »). |
| `page_perso.html` | Première version de la page, avec un formulaire prénom / email. |
| `style.css` | Feuille de style commune aux deux pages (mise en page flex et grid, cartes, listes). |
| `Ben_quai_Redim.jpg` | Photo affichée en haut de la page (version redimensionnée de `Ben_quai.jpg`). |
| `notes.txt` | Notes personnelles. |

## Voir le site

### Option 1 : ouvrir le fichier directement

Aucune installation n'est nécessaire. Double-clique sur `index.html`, ou depuis Git Bash :

```bash
start index.html
```

### Option 2 : lancer un petit serveur local

Depuis le dossier du projet :

```bash
python -m http.server 8000
```

Puis ouvre <http://localhost:8000> dans ton navigateur. Arrête le serveur avec `Ctrl + C`.

Avec VS Code, l'extension **Live Server** (clic droit sur `index.html` → *Open with Live Server*) recharge la page à chaque modification.

### Option 3 : GitHub Pages

1. Sur GitHub : *Settings → Pages*.
2. Dans *Build and deployment*, choisis la branche à publier (par exemple `main`) et le dossier `/ (root)`.
3. Le site est ensuite disponible à l'adresse `https://benrochet.github.io/Page_perso_HTML/`.

## Récupérer le projet

```bash
git clone https://github.com/BenRochet/Page_perso_HTML.git
cd Page_perso_HTML
```

## Technologies

- HTML5
- CSS3 (flexbox, grid, media queries)
- Police [Lato](https://fonts.google.com/specimen/Lato) via Google Fonts (connexion internet requise pour son chargement)

## Auteur

Benjamin — [@BenRochet](https://github.com/BenRochet)
