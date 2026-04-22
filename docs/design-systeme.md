🎨 1. design-systeme.md

`md

Design System — Site Web La Roulotte Solidaire Toulouse

Ce document définit les règles visuelles, typographiques et structurelles du site.  
Il garantit une cohérence graphique et facilite les contributions.

---

1. Identité visuelle

Couleurs principales

| Nom | Valeur | Usage |
|-----|--------|-------|
| Primary | #e4572e | Boutons, accents, éléments importants |
| Primary Dark | #b53f1c | Hover, états actifs |
| Background | #f7f4ef | Fond clair |
| Surface | #ffffff | Cartes, blocs, navigation |
| Text | #222222 | Texte principal |
| Muted | #666666 | Texte secondaire |
| Accent | #1f6feb | Liens, focus |

Mode sombre (automatique)

Le site utilise prefers-color-scheme: dark pour adapter :

- fond  
- surfaces  
- textes  
- ombres  

---

2. Typographie

- Police : system-ui (rapide, accessible, universelle)
- Taille de base : 16px
- Échelle responsive :  
  clamp(1rem, 0.9rem + 0.5vw, 1.15rem)

Hiérarchie

- h1 : titre principal (page)
- h2 : sections
- h3 : sous-sections
- p : texte courant

---

3. Grilles & Layout

Grille principale

- Largeur max : 1080px
- Marges latérales : 1.25rem
- Grilles fluides :

`
grid-template-columns: repeat(auto-fit, minmax(270px, 1fr));
`

Breakpoints

- 900px : passage hero → 1 colonne  
- 720px : navigation compacte  
- 480px : typographie réduite

---

4. Composants

Boutons

- .btn
- .btn-primary
- .btn-outline

Cartes

- .card
- .info-block
- .hero-side

Badges

- .badge

Grilles

- .cards
- .info-grid

---

5. Accessibilité

- Focus visible renforcé
- Contrastes élevés
- Typographie scalable
- Navigation claire et cohérente

---

6. Animations

- Transitions douces : 0.25s ease
- Hover léger : translation -2px
- Ombres progressives

---

7. Évolutions possibles

- Thème clair/sombre manuel
- Composants CSS modulaires
- Palette étendue (success, warning, info)
`

---

🎨 2. contribution-guide_visuelle.md

`md

Guide de contribution visuelle
Site Web La Roulotte Solidaire Toulouse

Ce guide explique comment contribuer à l’aspect visuel du site : design, CSS, structure graphique.

---

1. Principes fondamentaux

- Simplicité  
- Lisibilité  
- Accessibilité  
- Cohérence  
- Respect du design system  

---

2. Structure visuelle des pages

Chaque page doit respecter :

- un header clair
- un main structuré en sections
- un footer simple
- des espacements cohérents

Espacements recommandés

- Entre sections : 2rem
- Dans les cartes : 1.3rem
- Marges latérales : 1.25rem

---

3. Règles CSS

À respecter

- Utiliser les variables CSS (var(--primary), etc.)
- Utiliser les classes existantes avant d’en créer de nouvelles
- Garder un CSS court, propre, commenté si nécessaire
- Respecter les breakpoints existants

À éviter

- Styles inline
- Couleurs en dur
- Multiplication de classes inutiles
- Ajout de frameworks lourds

---

4. Composants visuels

Boutons

- Toujours utiliser .btn-primary ou .btn-outline
- Pas de nouvelles variantes sans justification

Cartes

- Utiliser .card ou .info-block
- Garder les ombres et rayons définis

Grilles

- Utiliser les grilles fluides existantes
- Ne pas fixer de largeurs en pixels

---

5. Images & médias

- Format recommandé : .jpg ou .png
- Taille max : 200–300 Ko
- Placer dans un futur dossier /assets/ (si ajouté)

---

6. Accessibilité visuelle

- Contraste suffisant
- Taille de texte lisible
- Focus visible
- Pas d’animations agressives

---

7. Processus de contribution visuelle

1. Ouvrir une issue (amélioration visuelle)
2. Proposer une maquette simple (même textuelle)
3. Modifier le CSS dans css/styles.css
4. Tester sur mobile
5. Ouvrir une Pull Request

---

8. Évolutions possibles

- Ajout d’un thème sombre manuel
- Ajout d’un guide typographique complet
- Ajout d’un système d’icônes
`

---

📚 3. Dossier /docs/ complet

Voici le contenu final du dossier :

`
docs/
├── architecture.md
├── contribution-guide_visuelle.md
├── design-system.md
├── structure.md
└── workflow.md
`

Tu as maintenant un dossier de documentation complet, professionnel, digne d’un vrai projet open‑source.

---
