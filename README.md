# SG Conseils — maquette de page d'accueil

Proposition de refonte de la page d'accueil du cabinet d'expertise comptable SG Conseils (Toulouse et Villefranche-de-Lauragais), conçue par PMC Marketing.

Maquette de présentation, non contractuelle : les contenus reprennent les informations publiques du cabinet et de son site actuel.

## Ouvrir la page

La page est autonome : un seul fichier `index.html`, avec ses styles et scripts intégrés.

```bash
python3 -m http.server 8080
```

Puis ouvrir http://localhost:8080 dans un navigateur.

## Ce que contient la page

- Héro avec un graphique 3D de pilotage (réalisé jusqu'à aujourd'hui, prévisionnel en rouge) qui réagit à la souris et au défilement
- Présentation du cabinet, compteurs et manifeste révélé au défilement
- Les sept métiers en défilement horizontal épinglé
- Cinq situations d'entrepreneur en cartes empilées
- Grille des plus-values et « bilan » Actif / Passif du partenariat
- Dirigeants, compétences et méthode en quatre étapes
- Carte stylisée des deux agences, contact et pied de page

## Technique

HTML, CSS et JavaScript sans build. Bibliothèques chargées depuis des CDN : Three.js 0.152, GSAP 3.12 avec ScrollTrigger, Lenis 1.1. Polices Google Fonts : Archivo, Instrument Serif, Michroma.
