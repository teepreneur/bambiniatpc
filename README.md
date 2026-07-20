# Bambini at PC — Premium Toddler Flashcards

[![Web App](https://img.shields.io/badge/Web%20App-Live-2CC5BD?style=for-the-badge)](https://atpc.bambinitracker.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-F5A623?style=for-the-badge)](LICENSE)

**Bambini at PC** is a premium, low-stimuli interactive web application designed specifically for toddler early learning. Featuring phonetic audio clips, inclusive representation, and cozy color-matching layouts, it offers a gentle, high-contrast visual environment that serves children cognitively.

---

## ✨ Features

- **8 Activity Categories**:
  - 🔤 **Words**: Multi-stage deck grouped by syllables (1-syllable and 2-syllable words).
  - 🗣️ **Phrases**: Daily routines (e.g., brushing teeth, washing hands, cleaning up) with parent/toddler interactions.
  - 🔢 **Numbers**: Counting interactive elements from 1 to 10.
  - 🎨 **Colors**: Premium color mapping with full-bleed cards.
  - 🔺 **Shapes**: Core geometric profiles for cognitive development.
  - 🦁 **Animals**: Standard and multi-syllable animal kingdoms.
  - 👃 **Body Parts**: Identifying head, eyes, nose, tummy, etc.
  - 🏃 **Actions**: Verbs like jump, run, walk, sit, clap, and sleep.
- **Low-Stimuli Flat-Vector Illustrations**: Features warm, inclusive, flat-vector character designs with coily/curly hair representation, gentle smiles, and soft backgrounds.
- **Dynamic Color Matching**: The card frame automatically samples and blends its background color with the loaded illustration for a modern, bezel-free look.
- **Accessibility Text Contrast**: Automatically standardizes text color depending on background brightness (YIQ standard), switching to a light theme for darker cards (e.g. bedtime scene) for optimal legibility.
- **Phonetic Audio clips**: Gentle, native pronunciations for all words, routines, and characters.
- **Premium Dark Mode**: Built-in *Midnight Mocha* theme adapting automatically to the device's light/dark system settings.
- **Progress Vine**: A cute, interactive leafy path showing the child's progress through the cards.
- **PWA Support**: Fully installable as an app on tablets, mobile phones, or desktop PCs.

---

## 🎨 Visual Design Principles

1. **Cognitive Clarity**: No busy background patterns, high-stimuli sparkles, or distracting gradients. The child focuses strictly on the word and the corresponding subject.
2. **Bezel-free Styling**: Seamless illustration-to-card borders.
3. **Inclusive Graphics**: Beautiful, authentic representation of Black children and families.
4. **Gentle Animations**: Micro-interactions like a soft breathing effect on active cards.

---

## 🛠️ Tech Stack

- **Core**: Vanilla HTML5, CSS3, and ECMAScript 6 JavaScript.
- **Dependencies**: None (pure client-side static site, no build step required).
- **SEO & Discoverability**: Semantic HTML structure, JSON-LD Schema schema tags, optimized meta OpenGraph properties, `robots.txt`, and automated `sitemap.xml`.

---

## 🚀 Local Setup

Since this is a lightweight, dependency-free static site, running it locally is simple:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/teepreneur/bambiniatpc.git
   cd bambiniatpc
   ```

2. **Serve the App**:
   You can serve the directory using any local web server. For example:
   * **Python 3**:
     ```bash
     python3 -m http.server 8000
     ```
   * **NodeJS (serve)**:
     ```bash
     npx serve
     ```

3. **Open the browser**:
   Navigate to `http://localhost:8000` (or `http://localhost:3000` depending on the port).

---

## 📦 Directory Structure

```
├── CNAME             # Custom domain configuration for GitHub Pages
├── index.html        # Main single-page application and stylesheet
├── manifest.json     # Progressive Web App (PWA) manifest
├── robots.txt        # SEO crawler configurations
├── sitemap.xml       # Search engine site index
├── assets/           
│   └── cards/        # Newly generated flat-vector PNG illustration assets
├── audios/           # Phonetic audio pronunciation assets (.m4a)
└── marketing/        # Logos, flyers, and branding resources
```

---

## 📄 License

This project is licensed under the MIT License.
