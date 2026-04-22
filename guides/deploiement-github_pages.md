# Guide de déploiement — GitHub Pages  
Site Web — La Roulotte Solidaire Toulouse

Ce document explique comment déployer ou redéployer le site via GitHub Pages.

---

## 1. Prérequis

- Un dépôt GitHub contenant les fichiers HTML/CSS
- Le workflow `.github/workflows/deploy.yml` déjà configuré
- La branche `main` active

---

## 2. Déploiement automatique (recommandé)

Le site se déploie automatiquement à chaque push sur `main`.

### Fonctionnement
1. Tu pushes du code sur `main`
2. GitHub Actions exécute le workflow `deploy.yml`
3. Le site est publié sur GitHub Pages

### URL du site
https://.github.io

---

## 3. Activer GitHub Pages (si ce n’est pas déjà fait)

1. Aller dans **Settings**
2. Section **Pages**
3. Source : **GitHub Actions**
4. Sauvegarder

---

## 4. Déploiement manuel (rarement nécessaire)

Si tu veux relancer un déploiement sans push :

1. Aller dans **Actions**
2. Sélectionner le workflow **Deploy Website**
3. Cliquer sur **Run workflow**

---

## 5. Vérifier le déploiement

- Aller dans l’onglet **Actions**
- Vérifier que le workflow est vert
- Ouvrir l’URL du site

---

## 6. Problèmes courants

### ❌ Le site ne se charge pas
- Vérifier que `index.html` est à la racine

### ❌ Page blanche
- Vérifier les chemins CSS :  
  `href="css/styles.css"`

### ❌ Workflow rouge
- Ouvrir les logs dans **Actions**
- Corriger l’erreur (souvent un fichier manquant)

---

## 7. Bonnes pratiques

- Toujours tester en local avant de pousser
- Garder la structure simple
- Ne jamais renommer `index.html`
- Ne pas déplacer le dossier `css/`

---

## 8. Évolutions possibles

- Déploiement multi‑environnements
- Prévisualisation des PR (Netlify/Vercel)
- Monitoring de disponibilité


