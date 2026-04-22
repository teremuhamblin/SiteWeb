###### STRUCTURE.md - markdown
# 📁 SiteWeb
###### (à placer à la racine selon ton organisation du projet)
>SiteWeb `La Roulotte Solidaire Toulouse`
- Ce document décrit l’architecture du dépôt et le rôle de chaque dossier/fichier.  
Le site est en HTML/CSS, simple, léger et optimisé pour GitHub Pages.

## 📂 Arborescence générale
### 📁 Structure
```text
SiteWeb/
      ├── .github/
           ├── ...
      ├── css/
           ├── ...
      ├── docs/
           ├── ...
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

### 📁 .github/
>Configuration GitHub
- Ce dossier contient tout ce qui concerne la gestion du projet, et non le site lui‑même.
```text
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
```

---

### 📁 css/

Contient la feuille de style principale du site :
```text
- styles.css  
  Version optimisée, responsive, avec dark mode automatique et design system.
```

---

### 📂 Docs/

Contient les fichiers de documentation nécessaire du projet 

### 📄 Fichiers de licence

- LICENSE-Code  
  Licence du code source (HTML/CSS).  
  >MIT

- LICENSE-Contenu  
  Licence des contenus (textes, images).  
  >CC0 (domaine public).

---

### 📄 README.md
>Page d’accueil du dépôt GitHub :  
présentation du projet, objectifs, déploiement, contribution.

---

### 🌐 Pages HTML du site
```text
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
```

---

### 🧱 Structure technique
```text
- Site statique (HTML + CSS)
- Aucun framework
- Compatible GitHub Pages
- Responsive + dark mode automatique
- Organisation simple et maintenable
```

---

###🔧 Évolutions possibles
```text
- Ajout d’un dossier /assets/ pour images
- Ajout d’un /docs/ pour documentation interne
- Ajout d’un formulaire de contact (via service externe)
- Version FR/EN
- Composants CSS réutilisables
```

---

### ✔️ Conclusion

>Cette structure est propre, claire, professionnelle et open‑source ready.  
Elle respecte les bonnes pratiques GitHub et permet une maintenance simple et durable.

`

---
