# Académie Florale — Website

Site statique HTML/CSS mirroring the design of [academie-florale.fr](https://academie-florale.fr) for Sybile Loppé's formation fleuriste indépendante.

## Stack
- HTML5 + CSS3 (custom design system, no framework)
- Google Fonts : Playfair Display, Onest, Libre Caslon Display, Roboto Mono
- Vanilla JS pour reveal-on-scroll et carrousel témoignages

## Structure
```
├── index.html          # landing complète (12 sections)
├── styles.css          # design system + composants
├── assets/images/      # hero + piliers + modules + témoignages
└── README.md
```

## Sections
1. Hero — image plein écran + promesse 90 jours + CTA
2. À qui s'adresse le Programme ?
3. Les piliers de l'Accompagnement (Formation / Mentorat / Communauté)
4. Le Programme Virale (VSL)
5. 6 modules détaillés (Fondamentaux, Botanique, Techniques, Art Floral, Vente, Marketing)
6. Créer une activité florale qui vous ressemble (citation Sybile)
7. L'accompagnement Académie Florale (2 ans, coachings, présentiel)
8. Ils ont osé se lancer (carrousel témoignages)
9. La Formatrice — Sybile Loppé
10. Devenez votre propre Patron(ne) épanouie (4 piliers)
11. FAQ (6 questions)
12. Footer

## Design tokens
- **Cream** #FCFAF7 (background)
- **Deep brown** #1E0D01 (text)
- **Orange** #FC4A00 (CTA + accents)
- Warm brown, coral gradient variants for hover states

## Ouvrir localement
Ouvrir `index.html` directement dans un navigateur (pas de build).
