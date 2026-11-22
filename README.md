# Portfolio – Coulibaly Tenena Louis Melvine

Portfolio de Coulibaly Tenena Louis Melvine, étudiant en L2 informatique (Génie Logiciel).

Site statique : **HTML + CSS séparés**, **Bootstrap 5** (chargé par CDN), responsive, 6 pages.
Il n'y a rien à installer ni à compiler.

La video de présentation (de même que celle avec le responsive présenté) est sur la première page du site (Accueil) ou le fichier index.html

## Structure du projet

```
portfolioMelvine/
├── index.html            accueil + cartes vers les autres pages
├── qui-je-suis.html      à propos, objectif, formation, langues
├── savoir-faire.html     compétences + certifications et badges Credly
├── realisations.html     3 projets (Akwaba Health, Amazon Scraper, Analyse comparative)
├── cv.html               CV affiché sur la page + téléchargement PDF
├── contact.html          e-mail et GitHub
├── css/
│   ├── style.css         styles du site
│   └── certifications.css  styles des badges Credly
├── documents/            CV_Coulibaly_Melvine.pdf
└── images/               photo de profil, capture Akwaba Health, bandeaux
```

## Lancer le site sur GitHub

Le site est hébergé par **GitHub Pages** : il n'y a rien à installer.

1. Ouvre le dépôt sur GitHub : **https://github.com/Uchiwarenoi/Portfolio**
2. Va dans **Settings → Pages → GitHub Pages → Visit site**
   

Le site se charge sur l'accueil (`index.html`). Bootstrap, les polices Google, les badges Credly et les vidéos Google Drive sont chargés depuis Internet.

### Tester le responsive
Sur le site en ligne, appuie sur `F12`, puis sur l'icône « appareil mobile » (`Ctrl + Maj + M`) pour voir le rendu sur téléphone et tablette.