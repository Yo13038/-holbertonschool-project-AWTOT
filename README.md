# 🗺️ A Weeb Tour in Tokyo

Bienvenue sur le dépôt du projet **A Weeb Tour in Tokyo** ! Ce site web interactif est un guide touristique conçu pour les passionnés de pop culture japonaise, de mangas, d'animés et de jeux vidéo, regroupant 10 lieux incontournables de la capitale nippone.

---

## 🚀 Fonctionnalités & Design

* **Carte Interactive (Image Map) :** Une carte de Tokyo au format cinéma (16/9) qui permet, en cliquant sur ses différentes zones, de descendre de manière fluide (`smooth scroll`) directement vers le lieu sélectionné.
* **Mise en page alternée :** Un agencement dynamique en "Z" (une fois l'image à gauche, une fois à droite) pour une lecture moderne et agréable.
* **Design Sakura / Tokyo City :** Un arrière-plan texturé d'une branche de cerisier (`background.png`) qui fait ressortir un thème coloré contrasté (Header vert forêt et titres/bordures d'images illuminés en **rose néon**).
* **Effet contours sur les textes :** Le titre principal utilise un effet de contour blanc (`text-stroke`) pour un rendu graphique percutant.

---

## 🛠️ Technologies Utilisées

* **HTML :** Structuration sémantique de la page (`<main>`, `<section>`, balises `<map>` et `<area>`).
* **CSS :** * Flexbox pour l'alignement et l'alternance automatique des blocs (`:nth-child(even)`).
  * Propriétés modernes (`aspect-ratio`, `object-fit`, `box-shadow` pour l'effet néon).

---

## 📂 Structure du Projet

```text
├── index.html          # Page principale du site
├── style.css           # Fichier des styles CSS
└── images/             # Dossier contenant toutes les illustrations
    ├── background.jpg  # Texture de fond (bois)
    ├── map.png         # Carte principale du parcours
    ├── totoro.png      # Image du Musée Ghibli
    └── ...             # Autres images des lieux (Gundam, Shibuya, etc.)