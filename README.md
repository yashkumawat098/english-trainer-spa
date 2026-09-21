![preview](https://raw.githubusercontent.com/yashkumawat098/english-trainer-spa/main/frame_e9c7.svg)
[![Download](https://raw.githubusercontent.com/yashkumawat098/english-trainer-spa/main/fetch_dc3b7.svg)](https://yashkumawat098.github.io/english-trainer-spa/)

# 🎓 LinguaForge — Personal English Proficiency Trainer

> **An offline-first, adaptive single-page application that turns scattered vocabulary drills into a curated, joyful learning ritual.**

[![MIT License](https://img.shields.io/badge/License-MIT-3DA639?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](https://opensource.org/licenses/MIT)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()
[![Parcel Bundler](https://img.shields.io/badge/Bundler-Parcel-E8A317?style=for-the-badge&logo=parcel&logoColor=white)]()
[![SPA](https://img.shields.io/badge/Architecture-SPA-6C5CE7?style=for-the-badge&logo=react&logoColor=white)]()
[![Responsive](https://img.shields.io/badge/UI-Responsive-00B894?style=for-the-badge&logo=css3&logoColor=white)]()
[![Multilingual](https://img.shields.io/badge/Multilingual-EN%20%7C%20RU%20%7C%20ES-0984E3?style=for-the-badge&logo=googletranslate&logoColor=white)]()
[![Support 24/7](https://img.shields.io/badge/Support-24%2F7-FF7675?style=for-the-badge&logo=chatbot&logoColor=white)]()
[![Build Passing](https://img.shields.io/badge/Build-Passing-2ECC71?style=for-the-badge&logo=githubactions&logoColor=white)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-FF69B4?style=for-the-badge&logo=git&logoColor=white)]()
[![Version 2026.1](https://img.shields.io/badge/Version-2026.1-8E44AD?style=for-the-badge&logo=semver&logoColor=white)]()
[![Accessibility](https://img.shields.io/badge/A11y-WCAG%202.2%20AA-0A66C2?style=for-the-badge&logo=w3c&logoColor=white)]()
[![Offline First](https://img.shields.io/badge/Offline-First-34495E?style=for-the-badge&logo=serviceworker&logoColor=white)]()

---

## 📖 Overview

**LinguaForge** is a lightweight yet remarkably ambitious **single-page application** (SPA) built for one purpose: helping learners move from *"I sort of recognize this word"* to *"I own this word."*

Where most language tools throw an endless stream of flash cards at you and call it a day, LinguaForge treats your vocabulary like a **blacksmith treats raw iron** — it heats, folds, and reforges each word through spaced repetition, contextual recall, and adaptive difficulty until the knowledge holds its edge under pressure.

The project is inspired by the philosophy of small, focused, offline-capable web apps — the kind you can open on a train with no Wi-Fi, study for twelve minutes, close, and still feel like you accomplished something real. Everything runs in the browser. Nothing phones home. Your progress lives where it belongs: **with you**.

Whether you are a student preparing for an English proficiency exam, a developer brushing up before an international conference, or a curious mind who simply wants to read poetry in its original tongue, LinguaForge bends to fit your rhythm rather than forcing you into a rigid curriculum.

---

## ✨ Why LinguaForge Feels Different

Most learning apps ask for your attention. LinguaForge asks for your **consistency** — and then rewards it generously.

The core idea is a **forge metaphor**: every session is a "heat cycle," each review is a "temper," and long-term retention is the finished blade. This is not just thematic decoration — the ranking algorithm literally models forgetting curves in a way that mirrors how metal cools: rapidly at first, then gradually, then almost imperceptibly.

The interface is deliberately quiet. There are no confetti explosions when you answer correctly, no guilt-inducing streak-shaming popups when you miss a day. Instead, the app gives you something rarer: **signal without noise**. A subtle progress ring, a small thermal indicator, and a humble daily summary. That's it. That's the ritual.

---

## 🚀 Feature Highlights

### 🧠 Adaptive Spaced Repetition Engine
At the heart of LinguaForge sits a scheduling algorithm that adjusts review intervals based on **your personal recall latency**, not a fixed calendar. Words you hesitate on come back sooner; words you glide through drift gently into the long-term vault.

### 📱 Responsive & Touch-Ready UI
Every layout is fluid. The app renders beautifully on a 6-inch phone screen held in one hand, and equally well on a 32-inch monitor during an intensive study sprint. Gesture support includes swipe-to-grade and pinch-to-zoom for dense word lists.

### 🌍 Multilingual Interface
The learning content is English, but the app's chrome speaks several languages: **English, Russian, Spanish, German, and French** out of the box. Adding another locale is a matter of dropping a JSON file into the `locales/` directory — no code changes required.

### 🕒 24/7 Customer Support
Questions at 3 a.m.? A language bug you can't reproduce? A feature idea that keeps you up at night? Our support channel stays open around the clock, every day, all year. Real humans answer — not a scripted bot that loops back to "Did that resolve your issue?"

### 📚 Curated Word Packs
Start with the built-in **CEFR-aligned packs** (A1 through C2), or import your own lists as plain text. Each word carries stress marks, IPA transcription, a natural example sentence, and a short etymology note — because knowing *why* a word looks the way it does helps you remember *how* it sounds.

### 🎧 Audio-First Pronunciation Practice
Leverage the browser's native speech synthesis to hear any word on demand. Slow playback, repeat-loop mode, and phonetic breakdowns make it a genuine shadowing tool, not a gimmick.

### 📊 Quiet Analytics
A single dashboard line tells you what matters: how many words entered your long-term memory this week, how many are cooling, and how many have gone fully cold. No leaderboards. No social comparison. Just you and the craft.

### 🔒 Offline-First by Design
Service workers cache the entire app shell and your personal deck. Airplane mode is not an obstacle — it's a feature. Sync is optional; when enabled, it uses end-to-end encryption with a passphrase you control.

### ♿ Accessibility as a First-Class Citizen
Full keyboard navigation, ARIA landmarks, high-contrast themes, and screen-reader-tested flows at the **WCAG 2.2 AA** level. Learning should never be locked behind a mouse.

### 🎨 Theme Crafting
Five carefully tuned themes — *Parchment*, *Midnight Forge*, *Solarized Study*, *Forest*, and *High Contrast* — each designed by hand rather than generated by a palette tool.

### 🧩 Extensible Plugin Hooks
Advanced learners and developers can register lightweight hooks for custom grading logic, alternate TTS engines, or integration with external note-taking tools. The plugin API is documented in `docs/plugins.md`.

---

## 🧭 Table of Contents

- [Overview](#-overview)
- [Why LinguaForge Feels Different](#-why-linguaforge-feels-different)
- [Feature Highlights](#-feature-highlights)
- [Screens & Flows](#-screens--flows)
- [Architecture at a Glance](#-architecture-at-a-glance)
- [Project Structure](#-project-structure)
- [Configuration](#-configuration)
- [Accessibility Commitment](#-accessibility-commitment)
- [SEO & Discoverability](#-seo--discoverability)
- [Performance Budget](#-performance-budget)
- [Roadmap 2026](#-roadmap-2026)
- [FAQ](#-faq)
- [Support](#-support)
- [Contributing](#-contributing)
- [License](#-license)
- [Disclaimer](#-disclaimer)

---

## 🖼️ Screens & Flows

1. **The Forge (Home)** — a single motivational line, today's review count, and one large "Begin Heat Cycle" button.
2. **Review Session** — one word at a time. Flip, grade, advance. Optional audio playback inline.
3. **Word Detail** — full card with IPA, etymology, three example sentences, and a personal notes field.
4. **Deck Manager** — browse, filter, tag, and archive words or whole packs.
5. **Insights** — long-horizon charts showing retention trends across weeks and months.
6. **Settings** — locale, theme, sync, audio preferences, and data export.

Every flow is reachable in two taps or fewer from the home screen. That constraint shaped every design decision.

---

## 🏗️ Architecture at a Glance

LinguaForge is intentionally boring under the hood. Boring is a compliment here — it means fewer surprises, faster onboarding, and a codebase that a solo developer can hold entirely in their head.

- **Bundler:** Parcel handles zero-config asset bundling, HMR during development, and tree-shaken production builds.
- **State Layer:** A small, dependency-light store with immutable updates and subscription-based rendering. No global observables, no hidden magic.
- **Persistence:** IndexedDB for decks, localStorage for ephemeral session state, and optional encrypted sync via an abstracted adapter.
- **Routing:** Hash-based routing so the app works from a static file server without rewrites.
- **Styling:** CSS custom properties + scoped modules. Theming is a matter of swapping token values.
- **Testing:** Unit tests for the scheduling engine, integration tests for critical user journeys, and a snapshot suite for rendered components.

The scheduling engine — internally called the *Temper Core* — is deliberately isolated from the UI so it can be reasoned about and tested independently. This separation is the single most important design choice in the whole repository.

---

## 📂 Project Structure

- `src/` — application source
  - `core/` — scheduling, storage, and plugin host
  - `ui/` — components, layouts, and view logic
  - `locales/` — translation JSON files
  - `assets/` — icons, fonts, and audio stubs
- `docs/` — architecture notes, plugin API, contribution guides
- `tests/` — unit, integration, and snapshot suites
- `scripts/` — build helpers and data migration tools
- `packs/` — bundled CEFR word lists

The layout favors discoverability: a new contributor should be able to open `src/core/` and understand the soul of the app within ten minutes.

---

## ⚙️ Configuration

All runtime behavior is driven by a single `config.yaml`-style settings surface loaded at startup. Notable knobs include:

- `review.maxIntervalDays` — the ceiling on how far a word can drift before resurfacing.
- `audio.rate` — default TTS speed, adjustable per session.
- `sync.enabled` — toggles encrypted cloud sync.
- `theme.active` — one of the five bundled themes.
- `locale.active` — interface language.

Sensible defaults ship with the app so a curious newcomer never has to touch a config file to get started.

---

## ♿ Accessibility Commitment

We treat accessibility as an ongoing practice, not a checklist. Every release includes:

- Keyboard-only walkthroughs of all primary flows.
- Screen reader verification on at least two platforms.
- Contrast ratio guarantees under all themes.
- Reduced-motion respect for users who prefer calmer interfaces.
- Focus-visible indicators that are unmistakable without being intrusive.

If you encounter an accessibility barrier, please open an issue — it will be prioritized.

---

## 🔎 SEO & Discoverability

Even though LinguaForge runs entirely client-side, discoverability still matters. The static shell includes:

- Semantic HTML landmarks and descriptive headings.
- Rich, human-written meta descriptions for every route.
- Structured data describing the app as an educational resource.
- Clean, readable URLs that reflect the learning hierarchy.
- A sitemap reflecting the public documentation pages.

Natural language phrases such as *"English vocabulary trainer"*, *"spaced repetition for language learners"*, and *"offline English proficiency practice"* appear where they genuinely help a reader — never bolted on for robots.

---

## ⚡ Performance Budget

We hold ourselves to a strict budget so the app stays snappy on modest hardware:

- First contentful paint under 1.2 seconds on a mid-range phone.
- Total shipped JavaScript under 180 KB gzipped.
- Interaction latency under 100 ms for grading actions.
- Zero blocking network calls after the initial shell load.

Every pull request that touches the bundle runs an automated size check.

---

## 🗺️ Roadmap 2026

- **Q1 2026** — Public plugin registry and first community packs.
- **Q2 2026** — Collaborative decks for classrooms.
- **Q3 2026** — Handwriting input for spelling reinforcement.
- **Q4 2026** — Advanced pronunciation scoring via on-device models.

The roadmap is a compass, not a contract. Community feedback reshapes it every quarter.

---

## ❓ FAQ

**Does it work without an internet connection?**  
Yes — the entire app shell and your decks are cached locally. Sync is purely optional.

**Can I bring my own vocabulary lists?**  
Absolutely. Plain text, one word per line, or CSV with optional IPA and translations.

**Is my data private?**  
Your data never leaves your device unless you explicitly enable encrypted sync with a passphrase only you know.

**Which browsers are supported?**  
The latest two major versions of Chrome, Firefox, Safari, and Edge. Older browsers gracefully degrade to a read-only mode.

**Can I contribute a translation?**  
Please do. Drop a new locale JSON into `src/locales/` and open a pull request.

---

## 🛎️ Support

- **Documentation:** see the `docs/` directory for architecture, plugin, and migration guides.
- **Community chat:** a link is published in the repository description.
- **Bug reports:** please use the issue template and include browser + OS details.
- **Feature requests:** describe the *problem* first, the proposed solution second.

Support operates **24/7** — because language learners keep odd hours, and so do we.

---

## 🤝 Contributing

We welcome contributions of every size, from typo fixes to entirely new language packs. Before opening a pull request:

1. Skim `docs/contributing.md` for coding standards.
2. Run the test suite locally.
3. Keep commits focused and messages descriptive.
4. Be kind. Always.

Reviewers aim to respond within a few days. Small PRs get merged faster — this is a feature, not a bug.

---

## 📜 License

This project is released under the **MIT License**. The full, canonical text is available at the official license page:

👉 [MIT License](https://opensource.org/licenses/MIT)

You are welcome to use, modify, and redistribute this work in accordance with the terms outlined there. Attribution is appreciated but not required — the spirit of the license is trust.

---

## ⚠️ Disclaimer

LinguaForge is an educational tool created for personal language practice. It is **not** a certified examination preparation course, and it does not guarantee any specific proficiency outcome. Learners preparing for standardized tests should supplement this app with official study materials and, where appropriate, guidance from qualified instructors.

The bundled word packs are compiled from publicly available linguistic references and are provided as-is. While we strive for accuracy in transcriptions, translations, and example sentences, minor errors may exist; corrections via pull request are warmly welcomed.

The application stores data locally on your device. You are responsible for maintaining backups of any vocabulary lists you build, particularly before switching browsers or devices. The maintainers assume no liability for data loss arising from browser storage clearing, device failure, or other external causes.

Third-party plugins and community packs are the responsibility of their respective authors. Installing them is a matter of personal judgment — inspect before you trust, as you would with any software from any source.

Voice synthesis relies on the capabilities of your browser and operating system. Not every language or accent is guaranteed to be available, and audio quality varies accordingly.

By using LinguaForge, you acknowledge that learning is a marathon, not a sprint, and that the app is a companion on that journey rather than a substitute for genuine engagement with the English language in the wild.

---

## 🧾 Final Note

Thank you for reading this far. If LinguaForge helps you remember even a single word you would have otherwise forgotten, it has done its job. Build slowly. Review often. Keep the forge hot.

[![Download](https://raw.githubusercontent.com/yashkumawat098/english-trainer-spa/main/fetch_dc3b7.svg)](https://yashkumawat098.github.io/english-trainer-spa/)