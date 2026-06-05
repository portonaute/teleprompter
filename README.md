# 🎙️ Teleprompter — Gratuit, 100 % personnalisable, propulsé par **Celestory**

[![Made with Celestory](https://img.shields.io/badge/Made%20with-Celestory-7C3AED?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI0ZGRiIgZD0iTTEyIDJMMiA3djEwbDEwIDV2M2wxMC01VjdMMTIgMnoiLz48L3N2Zz4=)](https://creator.celestory.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](teleprompter.html)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)

> **Un teleprompteur professionnel, gratuit, sans installation, qui tourne dans n’importe quel navigateur — et qui s’insère nativement dans vos projets Celestory.**

---

## 🇫🇷 **Français**

### ✨ Pourquoi ce teleprompteur ?

Pour **tous les créateurs de contenus** — youtubers, formateurs, conférenciers, streamers, podcasteurs, comédiens — **avoir un bon teleprompteur gratuit est essentiel** :  
pas de budget pour du matériel pro, pas de logiciel lourd à installer, pas de watermark, pas de limite de temps. Juste **un outil qui marche, tout de suite, partout**.

### 🚀 Fonctionnalités clés

| Fonction | Détail |
|----------|--------|
| **Défilement fluide & configurable** | Vitesse 0.25× → 4×, pas de 0.25×, pas de saccade |
| **Taille de police & largeur** | 20 → 150 px, largeur 50 % → 100 % viewport |
| **4 orientations** | Portrait, Portrait miroir, Paysage, Paysage miroir (idéal pour téléprompteurs physiques) |
| **Couleurs 100 % personnalisables** | Texte, H1/H2/H3, Gras, fond des menus `<details>`, titre des menus |
| **Raccourcis clavier** | `Espace` = Play/Pause · `D` = +vitesse · `S` = -vitesse |
| **Contrôles rétractables** | Bouton flottant → panneau complet (Tailwind + backdrop-blur) |
| **Markdown-like rendering** | Titres, listes, gras, `<details>/<summary>` rendus nativement |
| **Zéro dépendance locale** | Un seul fichier `teleprompter.html` — fonctionne *offline* une fois chargé |
| **Export / Intégration Celestory** | Copiez le bloc HTML5 dans **Celestory Creator** → insérez-le dans n’importe quel scénario (chatbot, visual novel, formation) |

### 🧩 Le bloc HTML5 sur **Celestory Creator**

Le code React/Tailwind complet est packagé en **un bloc HTML5 autonome** prêt à l’emploi :

🔗 **Projet Celestory Creator** → [https://creator.celestory.io/project/35kbwA-1w](https://creator.celestory.io/project/35kbwA-1w)

> Dans l’éditeur Celestory : *Ajouter un bloc → HTML5 → Coller le code → Publier*.  
> Le teleprompteur devient alors un **composant réutilisable** dans vos expériences interactives.

### 🌌 Intégration dans l’écosystème **Celestory**

| Cas d’usage | Comment ça s’insère |
|-------------|---------------------|
| **Formation interactive** | Affichez le script du formateur en overlay pendant l’enregistrement vidéo |
| **Visual Novel / Jeux narratifs** | Télé-prompt pour les doubleurs / voice-actors pendant la session d’enregistrement |
| **Chatbot / Avatar IA** | Synchronisez le texte défilant avec la synthèse vocale (TTS) pour un présentateur virtuel parfait |
| **Présentation live / Conférence** | Lancez le fichier HTML sur un second écran / tablette → mode miroir pour vitre de teleprompteur physique |
| **Accessibilité** | Taille de police géante, contraste personnalisé → confort lecture pour tous |

> **Celestory** = plateforme no-code pour créer **jeux vidéo, formations, chatbots, visual novels** sans écrire de code (ou avec du JS custom si besoin).  
> Ce teleprompteur illustre la puissance des **blocs HTML5** : n’importe quel composant React/Vue/Svelte/Vanilla peut devenir un *building block* réutilisable dans vos scénarios.

### 🛠️ Utilisation rapide

```bash
# 1. Clonez ou téléchargez teleprompter.html
git clone https://github.com/portonaute/teleprompter.git
cd teleprompter

# 2. Ouvrez simplement le fichier dans votre navigateur
#    (double-clic ou `open teleprompter.html` / `xdg-open teleprompter.html`)
```

> **Aucun `npm install`, aucun build, aucun serveur requis.**  
> Le CDN Tailwind + React/Babel chargent à la volée.

### 🎨 Personnalisation avancée

Modifiez les constantes en haut du `<script type="text/babel">` :

```js
const DEFAULT_TEXT = `Votre script ici…`;   // Supporte <h1>, <strong>, <details>, etc.
const TICK_MS = 40;                         // Fréquence rafraîchissement scroll
const BASE_SCROLL_PX = 2;                   // Vitesse de base
const SPEED_STEP = 0.25;                    // Incrément vitesse
// … MIN_SPEED, MAX_SPEED, MIN_FONT_SIZE, MAX_FONT_SIZE, MIN_WIDTH, MAX_WIDTH
const INITIAL_COLORS = { … };               // Palette par défaut
```

### 📦 Export & Partage

- **Fichier unique** → glisser-déposer sur clé USB, envoyer par mail, héberger sur GitHub Pages / Netlify / Vercel en 1 clic.
- **Intégration Celestory** → le bloc HTML5 reste **éditable** dans le Creator (vous changez le texte par défaut, les couleurs, etc. sans toucher au code).

### 🤝 Contribuer

1. Fork → branche `feature/…`  
2. Modifiez `teleprompter.html` (le code est tout dedans)  
3. PR avec description claire + captures d’écran si UI

### 📄 Licence

**MIT** — libre d’usage, de modification, de redistribution, y compris commercial.  
*Cœur ❤️ par l’équipe Celestory & la communauté no-code.*

---

## 🇬🇧 **English**

### ✨ Why this teleprompter?

For **every content creator** — YouTubers, trainers, speakers, streamers, podcasters, actors — **having a great free teleprompter is essential**:  
no budget for pro gear, no heavy software to install, no watermark, no time limit. Just **a tool that works, instantly, anywhere**.

### 🚀 Key Features

| Feature | Detail |
|---------|--------|
| **Smooth, configurable scrolling** | Speed 0.25× → 4×, 0.25× steps, zero jitter |
| **Font size & width** | 20 → 150 px, width 50 % → 100 % viewport |
| **4 orientations** | Portrait, Portrait Mirrored, Landscape, Landscape Mirrored (perfect for physical teleprompter rigs) |
| **100 % customizable colors** | Text, H1/H2/H3, Bold, `<details>` background, summary title |
| **Keyboard shortcuts** | `Space` = Play/Pause · `D` = faster · `S` = slower |
| **Collapsible controls** | Floating button → full panel (Tailwind + backdrop-blur) |
| **Markdown-like rendering** | Headings, lists, bold, `<details>/<summary>` rendered natively |
| **Zero local dependencies** | Single `teleprompter.html` — works *offline* once loaded |
| **Export / Celestory integration** | Copy the HTML5 block into **Celestory Creator** → drop it into any scenario (chatbot, visual novel, training) |

### 🧩 The HTML5 Block on **Celestory Creator**

The full React/Tailwind code is packaged as a **standalone HTML5 block** ready to use:

🔗 **Celestory Creator Project** → [https://creator.celestory.io/project/35kbwA-1w](https://creator.celestory.io/project/35kbwA-1w)

> In the Celestory editor: *Add Block → HTML5 → Paste Code → Publish*.  
> The teleprompter becomes a **reusable component** inside your interactive experiences.

### 🌌 Integration in the **Celestory** Ecosystem

| Use Case | How it fits |
|----------|-------------|
| **Interactive Training** | Show the trainer’s script as an overlay while recording video |
| **Visual Novel / Narrative Games** | Teleprompt for voice actors during recording sessions |
| **Chatbot / AI Avatar** | Sync scrolling text with TTS for a flawless virtual presenter |
| **Live Presentation / Conference** | Run the HTML on a second screen / tablet → mirror mode for physical teleprompter glass |
| **Accessibility** | Huge font sizes, custom contrast → reading comfort for everyone |

> **Celestory** = no-code platform to create **video games, training modules, chatbots, visual novels** without writing code (or with custom JS when needed).  
> This teleprompter showcases the power of **HTML5 blocks**: any React/Vue/Svelte/Vanilla component can become a *reusable building block* in your scenarios.

### 🛠️ Quick Start

```bash
# 1. Clone or download teleprompter.html
git clone https://github.com/portonaute/teleprompter.git
cd teleprompter

# 2. Open the file in your browser
#    (double-click or `open teleprompter.html` / `xdg-open teleprompter.html`)
```

> **No `npm install`, no build, no server required.**  
> Tailwind + React/Babel load via CDN on the fly.

### 🎨 Advanced Customization

Edit the constants at the top of the `<script type="text/babel">` block:

```js
const DEFAULT_TEXT = `Your script here…`;   // Supports <h1>, <strong>, <details>, etc.
const TICK_MS = 40;                         // Scroll refresh interval
const BASE_SCROLL_PX = 2;                   // Base scroll speed
const SPEED_STEP = 0.25;                    // Speed increment
// … MIN_SPEED, MAX_SPEED, MIN_FONT_SIZE, MAX_FONT_SIZE, MIN_WIDTH, MAX_WIDTH
const INITIAL_COLORS = { … };               // Default color palette
```

### 📦 Export & Share

- **Single file** → drag to USB, email, host on GitHub Pages / Netlify / Vercel in one click.
- **Celestory Integration** → the HTML5 block stays **editable** in the Creator (change default text, colors, etc. without touching code).

### 🤝 Contributing

1. Fork → branch `feature/…`  
2. Edit `teleprompter.html` (everything is in there)  
3. PR with clear description + screenshots if UI changes

### 📄 License

**MIT** — free to use, modify, redistribute, including commercially.  
*Made with ❤️ by the Celestory team & the no-code community.*

---

## 🔗 Liens utiles / Useful Links

- **Celestory Creator** — [https://creator.celestory.io](https://creator.celestory.io)
- **Projet Teleprompteur sur Celestory** — [https://creator.celestory.io/project/35kbwA-1w](https://creator.celestory.io/project/35kbwA-1w)
- **Dépôt GitHub** — [https://github.com/portonaute/teleprompter](https://github.com/portonaute/teleprompter)
- **Documentation Celestory (blocs HTML5)** — [https://docs.celestory.io/blocks/html5](https://docs.celestory.io/blocks/html5)

---

> **Prêt à tourner ?** → Ouvrez `teleprompter.html`, collez votre script, réglez la vitesse, et **enregistrez comme un pro — gratuitement, pour toujours.**
