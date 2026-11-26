# MON BUDGET — Prototype V1

Application web simple en français pour suivre les revenus, les dépenses et les soldes de plusieurs comptes en FCFA.

## Fonctionnalités
- Solde total et totaux mensuels affichés sur l’accueil.
- Ajout, modification et suppression de revenus et dépenses.
- Gestion de comptes et transferts entre comptes.
- Analyse par période et répartition par catégorie.
- Historique des opérations.
- Fonctionnement hors ligne après le premier chargement sur un hébergement compatible HTTPS.

## Structure
```text
mon-budget/
├── index.html
├── manifest.webmanifest
├── README.md
├── service-worker.js
├── app.js
└── styles.css
```

## Lancer le prototype
Ouvrir `index.html` dans un navigateur pour un aperçu. Pour tester l’installation et le mode hors ligne, publier le projet sur un hébergement HTTPS (par exemple GitHub Pages).

## À savoir
Cette version stocke les données localement dans le navigateur de l’appareil (`localStorage`). Les données ne sont pas synchronisées entre appareils et ne sont pas sauvegardées sur un serveur. Ne pas utiliser cette version de démonstration pour stocker des informations financières sensibles.
