# Ciao Senda — Italiano A1 → A2

**Restaurant & Interview Training**
_Impara l'italiano. Parla con sicurezza. Lavora con i clienti._

A single-page Italian training app built for restaurant work and a job interview
(Cameriera di Sala / Runner). No build step, no server, no dependencies — one HTML file.

## What's inside

| Area | Content |
|---|---|
| **Learn** | 15 A1 lessons, 12 A2 lessons, 20 grammar lessons, 38-verb Verb Lab (present / past / future), question words, 40 vocabulary cards |
| **Speak** | 6 monologues with sentence audio + shadowing, AI speaking coach that scores you, pronunciation rules |
| **Listen** | 12 dialogues at four speeds, including chef instructions and fast Italian |
| **Restaurant** | 15 service modules, 12 customer scenarios, wine module, full shift simulation |
| **Equilibrio** | Restaurant concept, menu and prices, 8 dish cards, wine list, interview research |
| **Interview** | 85 questions with A1/A2 answers, interview simulator, chef simulator |
| **Assess** | Level exam with CEFR band report, statistics by skill, 28 achievements, readiness tracker, certificate |

## Features

- **Audio** — browser speech synthesis (Italian voice), adjustable speed, sentence-by-sentence shadowing
- **Speech scoring** — Web Speech API listens to you and scores accuracy, completeness, fluency, pronunciation (Chrome only)
- **Progress saved** — everything stored in `localStorage`, with JSON export/import
- **Level tracking** — every answer is logged; the app estimates a CEFR band from accuracy + coverage
- **Dark mode**, responsive layout, full keyboard/mobile navigation

## Run it

Open `index.html` in a browser. That's it.

For speech scoring and the best Italian voice, use **Google Chrome**.

## Deploy on GitHub Pages

1. Create a repository (Public), e.g. `ciao-senda`
2. Upload `index.html`, `README.md` and `.nojekyll`
3. **Settings → Pages → Source: Deploy from a branch → `main` / `root` → Save**
4. Wait ~1 minute. The site is live at `https://<username>.github.io/ciao-senda/`

## Tech

Vanilla HTML/CSS/JS. Hash router, no framework, no external requests.
Fonts: Lora (headings) + Inter/Carlito (body), with system fallbacks.

## Note on content

The Equilibrio restaurant data (dishes, ingredients, prices, concept) comes only from
material supplied by the restaurant. Nothing about ingredients or allergens is invented —
where information is missing, the app teaches the correct answer instead:
_«Un momento, controllo con la cucina.»_
