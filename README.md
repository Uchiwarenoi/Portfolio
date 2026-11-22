# Portfolio – Coulibaly Tenena Louis Melvine

Portfolio d'un étudiant en L2 informatique (Génie Logiciel) en recherche d'alternance.

Site statique : **HTML + CSS séparés**, **Bootstrap 5** (chargé par CDN), responsive, 6 pages.
Il n'y a rien à installer ni à compiler.

La video de présentation est sur la première page du site (Accueil) ou le fichier index.html

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
2. Va dans **Settings → Pages → Build and deployment**
   - Source : *Deploy from a branch*
   - Branch : `main`, dossier `/ (root)` → **Save**
3. Après 1 à 2 minutes, le site est en ligne : **https://uchiwarenoi.github.io/Portfolio/**

Le site se charge sur l'accueil (`index.html`). Bootstrap, les polices Google, les badges Credly et les vidéos Google Drive sont chargés depuis Internet.

### Tester le responsive
Sur le site en ligne, appuie sur `F12`, puis sur l'icône « appareil mobile » (`Ctrl + Maj + M`) pour voir le rendu sur téléphone et tablette.

## Modifier le contenu

| Je veux changer… | Fichier |
|---|---|
| mon nom, le menu | le bloc `<nav>` de **chaque** page `.html` (il est répété dans les 6 fichiers) |
| ma photo | remplacer `images/photo.jpg` (même nom) |
| la formation, les langues | `qui-je-suis.html` |
| les compétences, les badges | `savoir-faire.html` |
| les projets | `realisations.html` |
| les 2 vidéos de présentation | section « Présentation en vidéo » de `index.html` |
| le CV affiché | `cv.html` |
| le CV à télécharger | remplacer `documents/CV_Coulibaly_Melvine.pdf` (même nom) |
| mon e-mail, mon GitHub | `contact.html` et le pied de page |
| les couleurs, les polices | variables au début de `css/style.css` |

### Ajouter une page
1. Copie un fichier existant (par exemple `contact.html`) sous un nouveau nom.
2. Ajoute la ligne `<li class="nav-item">…</li>` correspondante dans le menu des 6 autres fichiers.

## Changer une vidéo de présentation (Google Drive)
1. Dans Google Drive : clic droit sur la vidéo → **Partager** → accès **« Tous les utilisateurs disposant du lien »**.
2. Copie le lien : `https://drive.google.com/file/d/IDENTIFIANT/view`
3. Dans `index.html`, remplace `IDENTIFIANT` dans les deux adresses de la vidéo concernée :
   `…/file/d/IDENTIFIANT/preview` (lecteur) et `…/file/d/IDENTIFIANT/view` (lien « Ouvrir dans Google Drive »).
