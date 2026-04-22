
🧩 workflow.md

`md

Workflow du projet — Site Web La Roulotte Solidaire Toulouse

Ce document décrit le fonctionnement interne du projet, du développement au déploiement.  
Le site est statique (HTML/CSS) et utilise GitHub Pages pour la mise en ligne.

---

1. Objectifs du workflow

- Maintenir un site simple, propre et accessible.
- Faciliter les contributions externes.
- Garantir un déploiement automatique et fiable.
- Assurer une qualité minimale du code (lint HTML/CSS).

---

2. Branches

main
- Branche principale.
- Contient la version en production du site.
- Chaque push déclenche un déploiement automatique.

Branches de travail
Nom conventionnel :

`
feature/nom-fonction
fix/nom-correctif
style/amelioration-css
content/mise-a-jour-texte
`

---

3. Processus de contribution

Étape 1 — Créer une issue
- Bug → template Bug Report
- Amélioration → template Feature Request
- Mise à jour de contenu → issue simple

Étape 2 — Créer une branche
`
git checkout -b feature/ajout-section
`

Étape 3 — Modifier le code
- HTML sémantique
- CSS propre, cohérent, responsive
- Respect du design system

Étape 4 — Ouvrir une Pull Request
- Le template PR s’applique automatiquement
- Vérification automatique via GitHub Actions :
  - Lint HTML
  - Lint CSS

Étape 5 — Revue & merge
- Validation via CODEOWNERS
- Merge → déploiement automatique

---

4. Déploiement automatique (GitHub Pages)

Le workflow deploy.yml :

- s’exécute à chaque push sur main
- génère un artefact contenant le site
- publie automatiquement sur GitHub Pages

URL finale du site :  
`
https://<ton-pseudo>.github.io/<nom-du-depot>/
`

---

5. Qualité & linting

Le workflow lint.yml vérifie :

- la validité HTML (HTMLHint)
- la qualité CSS (stylelint)

Objectif :  
➡️ éviter les erreurs courantes  
➡️ maintenir un code propre et lisible

---

6. Structure du site

- Pages HTML statiques
- Un seul fichier CSS global
- Pas de JS (sauf besoin futur)
- Dark mode automatique via CSS

---

7. Évolutions possibles

- Ajout d’un mode clair/sombre manuel
- Ajout d’un dossier /assets/ pour les images
- Ajout d’un changelog automatisé
- Ajout d’un système de composants CSS

---

8. Conclusion

Ce workflow garantit un projet :

- simple à maintenir  
- facile à contribuer  
- stable et automatiquement déployé  
- conforme aux bonnes pratiques open‑source  
`

---
