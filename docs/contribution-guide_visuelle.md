# Guide de contribution visuelle  
Site Web La Roulotte Solidaire Toulouse

Ce guide explique comment contribuer à l’aspect visuel du site : design, CSS, structure graphique.

---

## 1. Principes fondamentaux

- Simplicité  
- Lisibilité  
- Accessibilité  
- Cohérence  
- Respect du design system  

---

## 2. Structure visuelle des pages

Chaque page doit respecter :

- un **header clair**
- un **main structuré en sections**
- un **footer simple**
- des **espacements cohérents**

### Espacements recommandés

- Entre sections : `2rem`
- Dans les cartes : `1.3rem`
- Marges latérales : `1.25rem`

---

## 3. Règles CSS

### À respecter

- Utiliser les **variables CSS** (`var(--primary)`, etc.)
- Utiliser les **classes existantes** avant d’en créer de nouvelles
- Garder un CSS **court, propre, commenté si nécessaire**
- Respecter les **breakpoints existants**

### À éviter

- Styles inline
- Couleurs en dur
- Multiplication de classes inutiles
- Ajout de frameworks lourds

---

## 4. Composants visuels

### Boutons

- Toujours utiliser `.btn-primary` ou `.btn-outline`
- Pas de nouvelles variantes sans justification

### Cartes

- Utiliser `.card` ou `.info-block`
- Garder les ombres et rayons définis

### Grilles

- Utiliser les grilles fluides existantes
- Ne pas fixer de largeurs en pixels

---

## 5. Images & médias

- Format recommandé : `.jpg` ou `.png`
- Taille max : 200–300 Ko
- Placer dans un futur dossier `/assets/` (si ajouté)

---

## 6. Accessibilité visuelle

- Contraste suffisant
- Taille de texte lisible
- Focus visible
- Pas d’animations agressives

---

## 7. Processus de contribution visuelle

1. Ouvrir une issue (amélioration visuelle)
2. Proposer une maquette simple (même textuelle)
3. Modifier le CSS dans `css/styles.css`
4. Tester sur mobile
5. Ouvrir une Pull Request

---

## 8. Évolutions possibles

- Ajout d’un thème sombre manuel
- Ajout d’un guide typographique complet
- Ajout d’un système d’icônes
