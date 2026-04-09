# ONBOARDING — Rejoindre le projet FlowMind (100% en ligne)

Bienvenue sur le projet **FlowMind** ! Ce guide te permet de contribuer au projet entièrement depuis GitHub, sans rien installer sur ton ordinateur.

---

## 1. Créer un compte GitHub

Si tu n'en as pas encore : [github.com/signup](https://github.com/signup)

Communique ton nom d'utilisateur GitHub à Romaric pour qu'il t'invite en tant que collaborateur.

---

## 2. Accepter l'invitation

Tu recevras un email de GitHub avec un lien **"Accept invitation"**. Clique dessus.

Tu as maintenant accès au dépôt : [github.com/romaricponcin/Flowmind](https://github.com/romaricponcin/Flowmind)

---

## 3. Créer ta branche de travail

1. Va sur [github.com/romaricponcin/Flowmind](https://github.com/romaricponcin/Flowmind)
2. Clique sur le menu déroulant des branches (en haut à gauche, affiche **"master"**)
3. Dans le champ de recherche, tape : `dev-utilisateur-B`
4. Clique sur **"Create branch: dev-utilisateur-B from master"**

Ta branche est créée. Tu travailleras uniquement sur celle-ci.

---

## 4. Modifier un fichier en ligne

1. Assure-toi d'être sur ta branche `dev-utilisateur-B` (vérifie le menu déroulant)
2. Navigue jusqu'au fichier à modifier (ex. `js/app.js`)
3. Clique sur l'icône **crayon** ✏️ en haut à droite du fichier
4. Fais tes modifications directement dans l'éditeur en ligne
5. En bas de page, section **"Commit changes"** :
   - Écris un message clair (ex. `feat: ajout du bouton X`)
   - Sélectionne **"Commit directly to dev-utilisateur-B"**
   - Clique **"Commit changes"**

---

## 5. Tester les modifications

Après chaque commit, tu peux tester directement depuis ton navigateur :

1. Va dans l'onglet **"Actions"** du dépôt
2. Ou ouvre simplement le fichier `index.html` depuis GitHub et clique **"Raw"**

> Pour un test complet, demande à Romaric d'activer GitHub Pages sur ta branche temporairement, ou teste localement en téléchargeant le dossier (bouton **"Code" → "Download ZIP"**).

---

## 6. Synchroniser avec les nouveautés de master

Avant de commencer à travailler, vérifie si `master` a évolué :

1. Va sur [github.com/romaricponcin/Flowmind/compare/dev-utilisateur-B...master](https://github.com/romaricponcin/Flowmind/compare/dev-utilisateur-B...master)
2. Si des commits apparaissent → clique **"Create pull request"** en inversant le sens : `base: dev-utilisateur-B ← compare: master`
3. Merge pour intégrer les nouveautés dans ta branche

---

## 7. Proposer tes modifications (Pull Request)

Quand ta fonctionnalité est prête :

1. Va sur [github.com/romaricponcin/Flowmind](https://github.com/romaricponcin/Flowmind)
2. Une bannière jaune apparaît : **"dev-utilisateur-B had recent pushes"** → clique **"Compare & pull request"**
3. Vérifie que la direction est : `base: master ← compare: dev-utilisateur-B`
4. Ajoute un titre clair et une description
5. Clique **"Create pull request"**
6. Romaric reçoit une notification, il review et valide le merge

**Ne jamais merger toi-même vers master — c'est Romaric qui valide.**

---

## 8. Ce qu'il ne faut jamais commiter

| Fichier | Raison |
|---|---|
| `flowmind-backup-*.json` | Données personnelles réelles |
| `flowmind-data*.json` | Idem |
| `js/seed-tne-drane.js` | Données d'établissements et de personnes réelles |

GitHub bloque automatiquement ces fichiers via `.gitignore` — mais reste vigilant lors de tes commits.

---

## 9. Règles complètes du workflow

Toutes les règles sont dans **`CLAUDE.md`** à la racine du projet.

---

## 10. Questions / Problèmes

Ouvre une **Issue** sur GitHub ou contacte Romaric directement.
