# 🌟 Projet Fansites — Hub Multi-Sites 

Plateforme web statique réalisée en **HTML5** et **CSS3**, réunissant plusieurs sites vitrines dédiés à des artistes, œuvres ou personnalités emblématiques. Chaque fansite dispose de son propre dossier et de son identité visuelle, reliés par une page d'accueil commune.

---

## 📋 Aperçu du projet

Ce dépôt regroupe l'ensemble des fansites développés dans le cadre du projet collaboratif :

* **Page d'accueil principale (`index.html`) :** Portail central permettant de naviguer vers chacun des fansites.
* **Fansite 1 — Freddie Mercury (`/fansite-queen`) :** Biographie, frise chronologique, discographie et galerie visuelle du groupe et de son chanteur emblématique.
* **Fansite 2 — Antoine Griezmann (`/fansite-2`) :** Présentation, actualités, réalisations marquantes et galerie dédiée.
* **Fansite 3 — Luis Carazo (`/fansite-3`) :** Histoire, œuvres clés, médias et ressources associées.

### Fonctionnalités communes
* **Architecture multi-pages :** Navigation fluide entre l'index général et les différentes sections de chaque fansite (Accueil, Histoire/Biographie, Galerie, Contact).
* **Identités graphiques distinctes :** Palettes de couleurs, typographies et mises en page personnalisées par univers.
* **Design Responsive :** Adaptation sur ordinateur, tablette et mobile grâce aux Media Queries, Flexbox et CSS Grid.

---

## 📁 Structure du dépôt

```text
Fansite-project/
├── index.html                  # Page portail principale (accès aux différents fansites)
├── css/
│   └── style.css               # Feuille de style de la page portail
├── assets/                     # Ressources globales (logos, icônes, polices)
│
├── fansite-queen/              # Dossier Fansite 1 : Freddie Mercury
│   ├── index.html
│   ├── css/
│   └── assets/
│
├── fansite-2/                  # Dossier Fansite 2 : Antoine Griezmann
│   ├── index.html
│   ├── css/
│   └── assets/
│
├── fansite-3/                  # Dossier Fansite 3 : Luis Carazo
│   ├── index.html
│   ├── css/
│   └── assets/
│
└── README.md                   # Documentation du projet
