###### STRUCTURE.md - markdown
# SiteWeb
```text
SiteWeb/
      ├── .github/
      ├── css/
      ├── LICENSE-Code
      ├── LICENSE-Contenu
      ├── README.md
      ├── actions.html
      ├── aider.html
      ├── index.html
      ├── infos.html
      └── mention-legale
```
---

📁 structure.md
###### (à placer à la racine selon ton organisation)
Structure du projet — Site Web La Roulotte Solidaire Toulouse

Ce document décrit l’architecture du dépôt et le rôle de chaque dossier/fichier.  
Le site est 100% HTML/CSS, simple, léger et optimisé pour GitHub Pages.

---

📂 Arborescence générale

`
/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   ├── workflows/
│   ├── CODEOWNERS
│   ├── CONTRIBUTING.md
│   ├── SECURITY.md
│   ├── SUPPORT.md
│   └── FUNDING.yml
│
├── css/
│   └── styles.css
│
├── LICENSE-Code
├── LICENSE-Contenu
├── README.md
│
├── index.html
├── actions.html
├── aider.html
├── infos.html
└── mention-legale.html
`

---

📁 .github/ — Configuration GitHub

Ce dossier contient tout ce qui concerne la gestion du projet, et non le site lui‑même.

- ISSUE_TEMPLATE/  
  Templates pour créer des issues (bug, amélioration, etc.)

- workflows/  
  Automatisations GitHub Actions (déploiement, linting, etc.)

- CODEOWNERS  
  Définit les responsables des revues de code.

- CONTRIBUTING.md  
  Guide pour contribuer au projet.

- SECURITY.md  
  Politique de sécurité et procédure de signalement.

- SUPPORT.md  
  Comment obtenir de l’aide.

- FUNDING.yml  
  Lien(s) de soutien ou de dons.

---

📁 css/

Contient la feuille de style principale du site :

- styles.css  
  Version optimisée, responsive, avec dark mode automatique et design system.

---

📄 Fichiers de licence

- LICENSE-Code  
  Licence du code source (HTML/CSS).  
  Généralement MIT ou CC0 selon ton choix.

- LICENSE-Contenu  
  Licence des contenus (textes, images).  
  Dans ton cas : CC0 (domaine public).

---

📄 README.md

Page d’accueil du dépôt GitHub :  
présentation du projet, objectifs, déploiement, contribution.

---

🌐 Pages HTML du site

- index.html  
  Page d’accueil du site.

- actions.html  
  Présentation des maraudes, collectes et événements.

- aider.html  
  Dons matériels, bénévolat, besoins prioritaires.

- infos.html  
  Adresse, accès, contact, réseaux sociaux.

- mention-legale.html  
  Mentions légales du site.

---

🧱 Structure technique

- Site statique (HTML + CSS)
- Aucun framework
- Compatible GitHub Pages
- Responsive + dark mode automatique
- Organisation simple et maintenable

---

🔧 Évolutions possibles

- Ajout d’un dossier /assets/ pour images
- Ajout d’un /docs/ pour documentation interne
- Ajout d’un formulaire de contact (via service externe)
- Version FR/EN
- Composants CSS réutilisables

---

✔️ Conclusion

Cette structure est propre, claire, professionnelle et open‑source ready.  
Elle respecte les bonnes pratiques GitHub et permet une maintenance simple et durable.

`

---
