# 🚀 Publier le site sur GitHub Pages — 5 minutes

Tu vas obtenir une URL du type `https://ton-username.github.io/playmed/` qui ouvre la page d'accueil avec les deux boutons.

---

## ÉTAPE 1 — Créer le repo sur GitHub

1. Va sur **https://github.com/new**
2. Remplis :
   - **Repository name** : `playmed` (ou ce que tu veux, en minuscules sans espaces)
   - **Description** : `PlayMed — Projet Master 2 Marketing Digital`
   - **Public** ✅ (obligatoire pour GitHub Pages gratuit)
   - **Add a README file** : NE PAS COCHER (on a déjà le nôtre)
3. Clique sur **Create repository**

---

## ÉTAPE 2 — Uploader les fichiers (drag & drop, sans terminal)

1. Sur la page de ton nouveau repo vide, clique sur le lien **"uploading an existing file"** (au milieu de la page) — ou va dans **Add file → Upload files**
2. **Glisse-dépose les 4 fichiers** suivants depuis le dossier `playmed-site` :
   - `index.html`
   - `etude-de-marche.html`
   - `identite-visuelle.html`
   - `README.md`
3. En bas de la page, dans "Commit changes" : laisse le message par défaut et clique **Commit changes**

---

## ÉTAPE 3 — Activer GitHub Pages

1. Dans ton repo, clique sur l'onglet **Settings** (en haut à droite)
2. Dans le menu de gauche, clique sur **Pages**
3. Sous **"Build and deployment"** :
   - **Source** : `Deploy from a branch`
   - **Branch** : sélectionne `main` puis `/ (root)` puis clique **Save**
4. Attends 1 à 2 minutes ⏳

---

## ÉTAPE 4 — Récupérer ton lien

Recharge la page **Settings → Pages**. En haut, tu verras :

> ✅ **Your site is live at https://ton-username.github.io/playmed/**

C'est **ce lien-là** que tu partages. Il ouvre la page d'accueil avec les deux boutons :
- **Étude de marché** → ouvre `etude-de-marche.html`
- **Identité visuelle** → ouvre `identite-visuelle.html`

---

## ✏️ Pour modifier plus tard

Sur GitHub, clique sur le fichier à modifier → icône crayon ✏️ → édite → **Commit changes**.
Le site se met à jour automatiquement en ~1 minute.

## 🆘 Si ça ne marche pas

- **404 sur le lien principal** : attends 2-3 min de plus, GitHub Pages met un peu de temps au premier déploiement
- **Les boutons ne marchent pas** : vérifie que les fichiers s'appellent bien `etude-de-marche.html` et `identite-visuelle.html` (pas de majuscule, des tirets et pas des espaces)
- **Page blanche** : vérifie que `index.html` est bien à la racine du repo (pas dans un sous-dossier)
