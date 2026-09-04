# 🎙️ Teleprompter — Gratuit, 100 % personnalisable, propulsé par **Celestory**

[![Made with Celestory](https://img.shields.io/badge/Made%20with-Celestory-7C3AED?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI0ZGRiIgZD0iTTEyIDJMMiA3djEwbDEwIDV2M2wxMC01VjdMMTIgMnoiLz48L3N2Zz4=)](https://creator.celestory.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](index.html)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)

> **Un téléprompteur professionnel, gratuit, sans installation, qui tourne dans n’importe quel navigateur — avec support complet Markdown (.md) et JSON, choix de la largeur de lecture, modes miroirs optiques, guide d'œil et défilement fluide.**

---

## 🇫🇷 **Français**

### ✨ Pourquoi ce téléprompteur ?

Pour **tous les créateurs de contenus** — youtubers, formateurs, conférenciers, streamers, podcasteurs, comédiens — **avoir un bon teleprompteur gratuit est essentiel** :  
pas de budget pour du matériel pro, pas de logiciel lourd à installer, pas de watermark, pas de limite de temps. Juste **un outil qui marche, tout de suite, partout**.

### 🚀 Fonctionnalités clés (v2.1)

| Fonction | Détail |
|----------|--------|
| **Support Markdown (.md) & HTML** | Rédigez, collez ou importez directement vos fichiers `.md` ou `.txt`. Barre d'outils Markdown intégrée (H1, H2, Gras, Listes, Notes). |
| **Largeur de texte ajustable** | De 30 % à 100 % de l'écran pour centrer la colonne de lecture sous l'objectif de caméra et réduire les mouvements d'yeux. |
| **Gestionnaire multi-scripts** | Stockez, basculez et gérez plusieurs discours avec sauvegarde automatique (`localStorage`), import/export JSON et import Markdown. |
| **Compte à rebours animé (3s)** | Lancement avec décompte visuel 3..2..1 pour se préparer face caméra avant le défilement. |
| **Défilement ultra-fluide** | Défilement 60 fps haute précision basé sur `requestAnimationFrame` et delta-time. |
| **Vitesse réglable** | De 0.2× à 5.0× avec incréments fins de 0.2× (clavier ou interface). |
| **Taille de police ajustable** | De 20 à 120 px avec boutons `A-`/`A+` ou touches fléchées gauche/droite. |
| **4 modes miroirs optiques** | Normal, Miroir horizontal, Miroir vertical, Miroir combiné (idéal pour vitres semi-réfléchissantes de prompteurs). |
| **Ligne repère d'œil (Eye-Line)** | Ligne guide rouge avec balises `►` et `◄` à 35% de la hauteur pour maintenir le contact visuel caméra. |
| **Raccourcis clavier complets** | `Espace` = Play/Pause · `↑`/`↓` = Vitesse · `←`/`→` = Taille · `[`/`]` = Largeur · `R` = Reset · `M` = Miroir · `G` = Repère · `F` = Plein écran |
| **Barre de contrôles rétractable** | Barre d'action flottante moderne Tailwind + backdrop-blur, masquable d'un clic. |
| **Zéro dépendance locale** | Fonctionne directement dans le navigateur via CDN ou déployé via Docker / Coolify. |

### ⌨️ Raccourcis Clavier

| Touche | Action |
|---|---|
| <kbd>Espace</kbd> | Lancer le compte à rebours ou Mettre en pause |
| <kbd>↑</kbd> / <kbd>↓</kbd> | Augmenter / Diminuer la vitesse (pas de 0.2x) |
| <kbd>→</kbd> / <kbd>←</kbd> | Augmenter / Diminuer la taille de police (pas de 4px) |
| <kbd>]</kbd> / <kbd>[</kbd> | Élargir / Rétrécir la colonne de lecture (pas de 5%) |
| <kbd>R</kbd> | Réinitialiser le prompteur en haut |
| <kbd>M</kbd> | Basculer entre les modes miroirs (Normal, H, V, Both) |
| <kbd>G</kbd> | Afficher ou masquer la ligne repère d'œil |
| <kbd>F</kbd> | Mode Plein Écran |
| <kbd>Échap</kbd> | Fermer le gestionnaire de scripts |

### 🛠️ Utilisation rapide

```bash
# 1. Clonez le dépôt
git clone https://github.com/portonaute/teleprompter.git
cd teleprompter

# 2. Ouvrez simplement index.html dans votre navigateur
open index.html
```

### 🐳 Déploiement Docker & Coolify

Un `Dockerfile` Nginx léger est inclus :

```bash
docker build -t teleprompter .
docker run -d -p 8080:80 teleprompter
```

Dans **Coolify** :
1. Créez une application depuis le dépôt GitHub `https://github.com/portonaute/teleprompter`.
2. Choisissez le buildpack `static` ou `dockerfile`.
3. Définissez le domaine cible (ex: `http://teleprompter.deploy.fr.nocodespacelab.com`).
4. Déployez en 1 clic !

---

## 🔗 Liens utiles / Useful Links

- **Application en ligne** — [https://teleprompter.deploy.fr.nocodespacelab.com](https://teleprompter.deploy.fr.nocodespacelab.com)
- **Celestory Creator** — [https://creator.celestory.io](https://creator.celestory.io)
- **Projet Teleprompteur sur Celestory** — [https://creator.celestory.io/project/35kbwA-1w](https://creator.celestory.io/project/35kbwA-1w)
- **Dépôt GitHub** — [https://github.com/portonaute/teleprompter](https://github.com/portonaute/teleprompter)
