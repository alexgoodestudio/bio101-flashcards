# BIO-101 Flashcards & Study Guide

An interactive, browser-based flashcard app for **BIO-101 (General Biology)**, built while studying for the course at **Midlands Technical College**. It's a single self-contained HTML file — no installs, no accounts, no dependencies. Open it and study.

**▶️ Live app:** https://alexgoodestudio.github.io/bio101-flashcards/

All content is aligned with **OpenStax *Biology 2e*** (the free, open textbook used in many community-college biology courses), organized chapter by chapter.

---

## Why this exists

I made this to get through BIO-101, and I'm sharing it in case it helps someone in a similar spot — community-college students, adult learners going back to school, anyone grinding through intro biology on a tight schedule. If that's you, I hope it saves you some time. Take it, use it, remix it.

---

## What it covers

Chapter-by-chapter review-question decks across the core intro-biology sequence, including:

- **Cells & metabolism** — cell structure, membranes & transport, enzymes, cellular respiration, photosynthesis
- **Genetics** — the cell cycle, mitosis & meiosis, Mendelian inheritance, chromosomal disorders
- **Molecular biology** — DNA structure & replication, transcription & translation, gene regulation
- **Evolution** — natural selection, speciation, population genetics & Hardy-Weinberg, phylogenetics
- **Ecology** — biomes, population & community ecology, symbiosis

Plus short-answer / essay practice decks and a dedicated **Final Prep** section.

---

## Features

- **Multiple-choice quiz mode** with instant right/wrong feedback and a running score
- **Answer mode** — flip straight to the answer for rapid recall self-testing
- **"Why" explanations** on every card, so you learn the reasoning, not just the answer
- **Memory tricks** — mnemonics and plain-English hooks for the concepts that are easy to mix up
- **Key-term tooltips** — tap/hover any highlighted term for its definition
- **"See in textbook" links** to the exact OpenStax section
- **Final Prep section** with three study tiers:
  - **All high-yield** — a broad curated review set
  - **⭐ Top Priority** — the tightest set of most-likely-tested concepts
  - **🧩 Diagrams** — label-and-function drills for cells, the Krebs cycle, photosynthesis, mitosis/meiosis, DNA, and more
- **Progress saving** — your marked cards and settings persist in your browser
- **Works on phone or desktop** — fully responsive

---

## How to use it

**Easiest:** just open the [live app](https://alexgoodestudio.github.io/bio101-flashcards/) in any browser.

**Run it locally:**
1. Download `index.html`
2. Double-click it — it opens in your browser and works completely offline

**Host your own copy (free, via GitHub Pages):**
1. Fork or copy this repo
2. Make sure the file is named `index.html` in the repo root
3. In your repo: **Settings → Pages → Deploy from a branch → main / (root) → Save**
4. Your copy goes live at `https://<your-username>.github.io/<repo-name>/`

---

## A note on the content

The questions are drawn from the review sections of **OpenStax *Biology 2e***, a free and openly licensed textbook. Explanations were written to teach the concepts in plain language. This is a **student-made study aid** — always defer to your own instructor, lectures, and course materials, since scope and emphasis vary from class to class. It's a supplement, not a substitute for the textbook or your professor.

---

## Tech

Plain HTML, CSS, and vanilla JavaScript in one file. No frameworks, no build step, no external libraries. Card data and study-set tiers live in simple JavaScript objects, and progress is stored in the browser's `localStorage`.

---

## License & sharing

Free to use, share, and adapt for studying. Content is based on OpenStax *Biology 2e*, which is licensed under Creative Commons Attribution (CC BY) — see [openstax.org](https://openstax.org/details/books/biology-2e).

If this helped you pass a class, that's the whole point. 🧬

---

*Built by Alex Goode while taking BIO-101 at Midlands Technical College. © 2026.*