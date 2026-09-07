# MotoCatalog

Site vitrine présentant un catalogue de motos sous forme de cartes (image + nom + catégorie). Projet développé en HTML/CSS pur, sans framework ni dépendance externe.

🔗 **Démo en ligne :** [https://lelelr.github.io/Site_Moto/](https://lelelr.github.io/Site_Moto/)

📅 **Dernière mise à jour :** 07/09/2026

## Aperçu

- Header avec logo et navigation
- Section hero d'introduction
- Grille de cartes responsive présentant chaque moto
- Thème sombre avec accent rouge, effets de survol sur les cartes
- Footer simple

## Structure du projet

```
Projet_DevOps/
├── index.html      # Structure de la page (header, hero, catalogue, footer)
├── style.css       # Mise en forme et thème du site
├── images/         # Photos des motos affichées dans le catalogue
└── README.md
```

## Catalogue actuel

| Moto                | Catégorie | Puissance |
|----------------------|-----------|-----------|
| BMW S1000RR          | Sportive  | 207 ch    |
| Honda CBR1000RR      | Sportive  | 189 ch    |
| BMW R1200GS          | Trail     | 125 ch    |
| Suzuki GSXS1000      | Roadster  | 152 ch    |
| Yamaha XSR700        | Roadster  | 75 ch     |

## Utilisation

Aucune installation nécessaire : ouvrir simplement le fichier `index.html` dans un navigateur.

## Ajouter une nouvelle moto

1. Placer l'image de la moto dans le dossier `images/`.
2. Dupliquer un bloc `<article class="moto-card">` dans `index.html`.
3. Mettre à jour le chemin `src` de l'image, le texte `alt`, le nom (`moto-card__name`) et la catégorie (`moto-card__category`).

## Technologies

- HTML5
- CSS3 (Flexbox, Grid, variables CSS)
