###### README.md - markdown
###### Mise à jour majeure : GitHub Pages + SPA + design system + composants + workflow CI/CD.

# 📘🌟 La Roulotte Solidaire Toulouse
- Site Web Officiel
>Bienvenue sur le dépôt du site web officiel de La Roulotte Solidaire Toulouse, une association engagée auprès des personnes à la rue, fondée sur la bienveillance, l’écoute et l’action concrète.
-Ce site est conçu comme une Single Page Application (SPA) moderne, rapide, animée et responsive, avec un design system avancé, un mode sombre automatique, un loader animé, des modales, des toasts, et une navigation fluide.

---

🚀 Fonctionnalités principales

🎨 Design & UI
- Design system complet (couleurs, espaces, radius, ombres…)
- Mode sombre automatique (basé sur prefers-color-scheme)
- Animations modernes (fade, reveal, parallax)
- Composants UI :
  - Header dynamique
  - Footer dynamique
  - Loader SPA animé
  - Modale interactive
  - Toast notifications

⚙️ Architecture technique
- SPA (Single Page Application) sans framework
- Navigation fluide sans rechargement
- Injection dynamique des composants
- Structure modulaire et maintenable
- Compatible GitHub Pages

📄 Pages disponibles
- Accueil
- Nos actions
- Nous aider
- Infos pratiques
- Contact
- Mentions légales
- À propos
- Notre équipe
- Nos partenaires
- Faire un don

---

📁 Structure du projet

```text
SiteWeb/
├── .gitkeeps           
├── pages/
│   ├── index.html
│   ├── actions.html
│   ├── aider.html
│   ├── infos.html
│   ├── contact.html
│   ├── mentions-legales.html
│   ├── a-propos.html
│   ├── notre-equipe.html
│   ├── nos-partenaires.html
│   └── faire-un-don.html
│
├── components/
│   ├── header.html
│   ├── footer.html
│   ├── loader.html
│   ├── modal.html
│   └── toast.html
│
├── css/
│   ├── system.css
│   ├── layout.css
│   └── styles.css
│
├── js/
│   └── layout.js
│
├── assets/
│   ├── hero.jpg
│   ├── logos/
│   └── images/
│
└── .github/
    └── .gitkeeps
    └── workflows/
        └── deploy.yml
        └── lint.yml
```

---

🔧 Installation & Déploiement

📌 Développement local
Aucun outil particulier n’est requis.

Il suffit d’ouvrir /pages/index.html dans un navigateur.

📌 Déploiement automatique (GitHub Pages)
Le site est déployé automatiquement via :

`
.github/workflows/deploy.yml
`

Le workflow :
- build le site
- upload l’artifact
- déploie sur GitHub Pages
- utilise l’environnement obligatoire github-pages

---

🧩 Fonctionnement du SPA

Le fichier js/layout.js gère :
- l’injection du header/footer
- le loader animé
- les transitions de pages
- les modales
- les toasts
- les animations reveal
- la navigation interne sans rechargement

Chaque lien interne .html est intercepté pour charger la page dynamiquement.

---

🎨 Design System

Le design system est défini dans :

`
css/system.css
`

Il contient :
- variables CSS globales
- couleurs
- espaces
- radius
- ombres
- transitions
- dark mode automatique

---

🤝 Contribution

Les contributions sont les bienvenues !

Merci de respecter :
- la structure du projet
- le design system
- les conventions CSS/JS
- la logique SPA

---

📜 Licence

Projet open-source sous licence MIT.  
Vous êtes libres de l’utiliser, modifier et redistribuer.

---

❤️ Remerciements

Merci à tous les bénévoles, partenaires et habitants de Toulouse qui soutiennent La Roulotte Solidaire.

Ensemble, nous créons du lien humain et de la solidarité.
`

---
# Version de base :
## 📘 La Roulotte Solidaire
## • `"Toulouse"`
### 🌿 Présentation
> Ce dépôt contient le site web officiel de  
`La Roulotte Solidaire Toulouse`, une association qui mène des `actions de solidarité` auprès des personnes à la rue : collectes, événements, soutien matériel et humain.
- Le site est volontairement simple, léger et accessible : HTML/CSS.

---

### 📂 Structure du projet

```text
SiteWeb/
└─ .github/
   └─ workflows/
   └─ ...
├─ index.html
├─ actions.html
├─ aider.html
├─ infos.html
├─ mentions-legales.html
└─ css/
   └─ styles.css
```
- .github/ — dossier de centralisation du projet 
- index.html — page d’accueil  
- actions.html — présentation des maraudes, collectes et événements  
- aider.html — dons matériels, bénévolat, besoins prioritaires  
- infos.html — adresse, accès, contact, réseaux sociaux  
- mentions-legales.html — mentions légales du site  
- css/styles.css — feuille de style principale

---

### 🚀 Déploiement
> Le site peut être hébergé gratuitement sur :
- Option 1 — GitHub Pages (recommandé)
```text
1. Créer un dépôt GitHub  
2. Ajouter tous les fichiers du site  
3. Aller dans Settings → Pages  
4. Source : Deploy from branch  
5. Branch : main + dossier /root  
6. Disponible à une URL du type :  
   https://votre-nom.github.io/laroulotte-solidaire-site/
```

- Option 2 — Netlify
```text
1. Glisser‑déposer le dossier dans https://app.netlify.com/drop
2. Déploiement instantané
```

- Option 3 — Vercel
```text
1. Importer le dépôt GitHub
2. Déploiement automatique
```

---

### 🧩 Contribution
> Les contributions sont les bienvenues :
- corrections de texte  
- amélioration du design  
- accessibilité  
- optimisation du CSS  
- ajout de pages ou sections  
- intégration d’un formulaire de contact  
- ajout d’un système de traduction FR/EN  

Pour contribuer :
1. Forker le dépôt  
2. Créer une branche :  
```text
git checkout -b amelioration-xyz
```
3. Faire vos modifications  
4. Ouvrir une Pull Request

---

### 📜 Licence
Le projet peut être publié sous double licence :
### Code (HTML/CSS)
➡️ Licence MIT — libre, permissive, adaptée à l’open‑source.

### Contenus (textes, visuels)
➡️ Licence Creative Commons CC BY‑NC 4.0  
Utilisation autorisée non commerciale, avec attribution.
```rst
(Tu peux modifier ces choix selon les besoins de l’association.)
```

---

### 🧭 Informations sur l’association

> La Roulotte Solidaire
- 11 Rue Charles Laganne  
- 31300 TOULOUSE
- Téléphone : 07 51 58 26 60  
- Email : laroulottesolidaire@gmail.com  
- Fb : facebook.com/laroulottesolidaire

---

### ❤️ Remerciements
> Merci à toutes les bénévoles, partenaires et personnes solidaires qui soutiennent La Roulotte Solidaire Toulouse.

---
