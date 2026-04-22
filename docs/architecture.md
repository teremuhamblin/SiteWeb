🧱 architecture.md

`md

Architecture du projet — Site Web La Roulotte Solidaire Toulouse

Ce document décrit l’architecture technique du site, les choix de conception et les principes structurants.

---

1. Vision générale

Le site est :

- statique (HTML + CSS)
- léger et rapide
- accessible
- responsive
- sans dépendances externes
- optimisé pour GitHub Pages

Objectif :  
➡️ un site simple, durable, facile à maintenir par n’importe quel bénévole.

---

2. Arborescence
```text
├── index.html        → accueil
├── actions.html      → nos actions
├── aider.html        → dons & bénévolat
├── infos.html        → infos pratiques
├── mention-legale.html
```

---

3. Structure HTML

Chaque page suit la même structure :

`
<header>   → navigation + identité
<main>     → contenu principal
<footer>   → mentions + liens
`

Principes :
- HTML sémantique (<section>, <article>, <nav>, <footer>)
- Titres hiérarchisés (h1 → h2 → h3)
- Pas de duplication inutile
- Code lisible et commenté si nécessaire

---

4. Architecture CSS

Le fichier styles.css repose sur :

🎨 Design System
- Variables CSS (:root)
- Couleurs
- Typographie
- Rayons
- Ombres
- Grilles

🌙 Dark mode automatique
Via prefers-color-scheme: dark.

📱 Responsive
- Grilles fluides (auto-fit, minmax)
- Breakpoints :
  - 900px
  - 720px
  - 480px

🧩 Composants CSS
- .hero
- .card
- .info-grid
- .btn, .btn-primary, .btn-outline
- .badge
- .footer-inner

🔒 Accessibilité
- Focus visible
- Contrastes renforcés
- Typographie scalable

---

5. Pages HTML

index.html
- Hero
- Présentation
- Actions
- CTA

actions.html
- Maraudes
- Collectes
- Événements

aider.html
- Dons matériels
- Bénévolat
- Relais d’information

infos.html
- Adresse
- Accès
- Réseaux sociaux

mention-legale.html
- Mentions légales
- Hébergement
- Propriété intellectuelle

---

6. Évolutions possibles

- Ajout d’un dossier /assets/ pour images
- Ajout d’un /docs/design-system.md
- Ajout d’un thème clair/sombre manuel
- Ajout d’un formulaire de contact (service externe)
- Internationalisation (FR/EN)

---

7. Conclusion

L’architecture est volontairement simple, robuste et accessible.  
Elle permet :

- une maintenance facile  
- une contribution ouverte  
- une évolution progressive  
- une performance optimale  
`

---
