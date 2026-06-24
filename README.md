# A Weeb Tour in Tokyo

Bienvenue sur le dépôt du projet **A Weeb Tour in Tokyo**. Ce site web interactif est un guide touristique conçu pour les passionnés de pop culture japonaise, de mangas, d'animés et de jeux vidéo, regroupant 10 lieux incontournables de la capitale nippone.

---

## Fonctionnalités & Design

* **Carte interactive :** une carte de Tokyo au format cinéma (16/9) présentée en haut de page (hero), encadrée et mise en valeur par une ombre rose néon. Chaque lieu y est cliquable (le point s'illumine au survol) et renvoie en douceur, par défilement fluide, vers la section correspondante.
* **Mise en page alternée :** un agencement en "Z" (image à gauche, puis à droite) grâce à Flexbox et au sélecteur `:nth-child(odd)` combiné à `flex-direction: row-reverse`.
* **Design responsive :** sur écran étroit (moins de 768px), les lieux passent automatiquement en une seule colonne (image au-dessus du texte) via une media query.
* **Thème Sakura / Tokyo City :** un arrière-plan de branche de cerisier (`images/fleur.png`) recouvert d'un voile blanc translucide (`linear-gradient`) pour garder le texte lisible. Contraste assumé : header vert forêt, titres et bordures d'images en rose néon.
* **Polices personnalisées (Google Fonts) :** "Mochiy Pop One" pour les titres et "M PLUS Rounded 1c" pour le texte, pour une ambiance japonaise tout en restant lisible.
* **Cartes de texte :** chaque description est posée sur un panneau blanc translucide, aux coins arrondis et bordé de rose.
* **Images arrondies :** bordure rose néon, coins arrondis et ombre douce sur chaque photo de lieu.
* **Effet contour sur le titre :** le titre principal utilise un contour blanc (`-webkit-text-stroke`).
* **Pied de page** assorti au header (vert et rose), avec un liseré rose.

---

## Technologies utilisées

* **HTML :** structuration sémantique de la page (`<header>`, `<main>`, `<section>`, `<footer>`).
* **CSS :**
  * Flexbox pour l'alignement et l'alternance des blocs (`:nth-child(odd)`).
  * Media query pour le responsive (`@media (max-width: 768px)`).
  * Propriétés modernes : `aspect-ratio`, `object-fit`, `box-shadow` (effet néon), `border-radius`, et `linear-gradient` (voile de fond).
  * Carte cliquable sans JavaScript : liens positionnés en pourcentage par-dessus l'image (`position: absolute`) et défilement fluide (`scroll-behavior: smooth`).
* **Google Fonts :** Mochiy Pop One et M PLUS Rounded 1c.

---

## Structure du projet

```text
├── index.html                 # Page principale du site
├── style.css                  # Feuille de styles CSS
├── README.md                  # Ce fichier
└── images/                    # Toutes les illustrations
    ├── map.png                # Carte du parcours (hero)
    ├── fleur.png              # Image de fond (cerisier / sakura)
    ├── totoro.png             # Musée Ghibli
    ├── shibuya_crossroad.png  # Carrefour de Shibuya
    ├── godzila.png            # Statue de Godzilla
    ├── gashapon.png           # Gashapon No Depato
    ├── TDCA.png               # Tokyo Dome City Attractions
    ├── cerisier.png           # Parc Ueno
    ├── akihabara.png          # Quartier d'Akihabara
    ├── sega_center.png        # Sega Center
    ├── okonomiyaki.png        # Okonomiyaki à Monja Street
    └── gundam.png             # Statue géante de Gundam
```

---

## Les 10 lieux du parcours

1. Musée Ghibli
2. Shibuya
3. Statue de Godzilla
4. Gashapon No Depato
5. Tokyo Dome City Attractions
6. Parc Ueno
7. Quartier d'Akihabara
8. Sega Center
9. Okonomiyaki à Monja Street
10. Statue géante de Gundam

---

## Lancer le projet

Le site est en HTML et CSS uniquement, sans dépendance.

1. Cloner le dépôt.
2. Ouvrir `index.html` dans un navigateur, ou utiliser l'extension Live Server de VS Code pour un aperçu avec rechargement automatique.

---

## Auteurs

Projet réalisé par **David** et **Yo**, dans le cadre de la formation **Holberton School**.
