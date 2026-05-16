# Contributing to The Brewing Bible

Thank you for considering a contribution. The Brewing Bible is built by brewers and fermenters around the world, and **every contribution matters** — from a single Verified Brew to a full recipe chapter.

This guide tells you everything you need to know to participate.

---

## Quick Start

**The 5-Minute Path (Verified Brew)**

The easiest way to contribute: brew an existing recipe from the Bible, then submit your feedback.

1. Pick a recipe from any of the [six books](./README.md#six-books)
2. Brew it yourself (any equipment, any scale)
3. Open a [new Issue](../../issues/new) using the "Verified Brew" template
4. Attach a photo of your result and a 1–5 star rating
5. Done — you've earned your first **Apprentice** credit

**The 30-Minute Path (Correction or Improvement)**

Found a typo, a wrong measurement, or a clearer way to explain something?

1. Fork the repository
2. Edit the relevant file
3. Open a Pull Request with a clear description
4. The maintainer team will review within 7 days

**The Multi-Hour Path (Translation)**

Help bring the Bible to other languages.

1. Find a recipe in English you'd like to translate
2. Open an Issue first to claim it (avoids duplicate work)
3. Create a translated file (e.g., `recipe-name.zh.md` for Chinese)
4. Submit as a Pull Request

**The Multi-Week Path (New Recipe Chapter)**

Want to add an entirely new recipe?

1. Read [TEMPLATE.md](./TEMPLATE.md) carefully
2. Open an Issue describing your proposed recipe (avoids duplicates and conflicts)
3. Wait for maintainer feedback before investing significant time
4. Write your chapter following the template structure
5. Submit as a Pull Request

---

## Before Your First Pull Request

By submitting a Pull Request, you agree to the [Contributor License Agreement (CLA)](./CLA.md). The CLA, in plain English:

- **You keep ownership** of what you write
- **The world can read your work for free** under CC BY-NC-SA 4.0
- **The maintainer can publish it commercially** (printed books, premium subscriptions, hardware integrations) — always with your name credited
- **You can use your own work elsewhere** (blog, your own book, anywhere)
- **You can't undo** once contributed — but your contribution remains permanently credited to you

See [CLA.md](./CLA.md) for full terms. If anything is unclear, open an Issue labeled `cla-question` before contributing.

---

## Contribution Rules

### What We Welcome

- **Original recipes** for any of the six books
- **Translations** into any language
- **Verified Brews** confirming recipes work as written
- **Corrections** to errors, outdated info, or unclear language
- **Variations** of existing recipes (e.g., low-sugar versions, regional adaptations)
- **Cross-references** linking related recipes across books

### What Belongs Elsewhere

- **Pure marketing content** (this is a knowledge base, not a product catalog)
- **Recipes that are commercial advertisements** for specific brands (mentioning brands as examples is fine; promoting them is not)
- **Content that violates third-party copyright** (including substantial copying from cookbooks, blogs, or commercial sources without permission)
- **Recipes without safety considerations** (especially for fermentation lab content involving `koji`, raw fish, etc.)

### Quality Standards

- **Recipes are written in English** (translations welcome; English is the source language)
- **Minimum 1,500 words, maximum 3,000 words** per full recipe chapter
- **Tested at least once** — Verified Brews preferred but not strictly required for first submissions
- **YAML frontmatter** must be complete (see TEMPLATE.md)
- **Original work or properly attributed** — see CLA Section 6

---

## Contributor Tiers

Tiers are how the project recognizes the depth and impact of your contributions over time.

| Tier | How to Reach It | Benefits |
|------|-----------------|----------|
| **Apprentice** | 1 merged contribution **or** 5 Verified Brews | • Repository credit on every recipe<br>• Digital Apprentice badge<br>• 100 BrewPoints |
| **Brewer** | 3 merged contributions **and** 10 Verified Brews | • All Apprentice benefits<br>• 30% off iGulu ingredient packs<br>• Credited in *Weekly Ferment* newsletter<br>• 500 BrewPoints |
| **Master Brewer** | 10 merged contributions **and** at least 1 recipe Verified by 10+ brewers | • All Brewer benefits<br>• Free iGulu starter device<br>• Editorial committee vote<br>• Name printed in the first edition book<br>• 2,000 BrewPoints |
| **Saint / Honorary Member** | Invited; the first 50 Founding Contributors automatically qualify | • All Master Brewer benefits<br>• Lifetime 40% iGulu discount<br>• Royalty share on printed editions<br>• Vote on major project decisions<br>• 5,000 BrewPoints + annual renewal |

**BrewPoints** can be redeemed at the iGulu store for ingredients, devices, or merchandise.

---

## The Six Books and Where to Contribute

| Book | Repository Path | What Belongs Here |
|------|----------------|-------------------|
| I. Foundations | `chapters/01_foundations` | Universal principles applicable across all fermentation traditions |
| II. Craft Beer | `chapters/02_craft-beer` | Ales, lagers, sours, specialty beers |
| III. Fruit Wine & Wine | `chapters/03_fruit-wine` | Grape wine, fruit wine, mead, cider, rice wine |
| IV. Probiotics | `chapters/04_probiotics` | Kombucha, kefir, yogurt, kvass, lacto-ferments |
| V. Cold-Brew & Mixology | `chapters/05_cold-brew` | Cold-brew, sparkling, hard seltzer, zero-proof |
| VI. Fermentation Lab | `chapters/06_fermentation-lab` | Vinegar, miso, soy sauce, sake, koji-based ferments |

If your contribution spans multiple books, open an Issue first — we'll help find the right home.

---

## Review Process

All Pull Requests go through three stages:

### Stage 1: Automated Validation (seconds)
Our CI checks YAML frontmatter, schema compliance, basic data consistency (e.g., does the calculated ABV match the stated OG/FG?), and Markdown validity. Failures are reported automatically — fix and re-push.

### Stage 2: Peer Review (within 7 days)
A community Reviewer (a Master Brewer or invited expert) checks:
- Scientific accuracy
- Adherence to the Bible's narrative template
- Whether the recipe duplicates or conflicts with existing content
- Whether attribution and citations are complete

You may receive requested changes — address them and push updates.

### Stage 3: Editorial Merge (within 3 days after Stage 2)
The Book's Lead Editor makes a final pass for style and consistency, then merges.

### Service Level Commitments
- **Issue triage**: 48 hours
- **First Reviewer response**: 7 days
- **Final merge after revisions**: 3 days

If your PR sits longer than these windows, ping `@maintainers` in the PR comments.

---

## Recognition Programs

### Quarterly Awards (every 3 months)
- **Best New Recipe** — most outstanding new chapter
- **Best Community Builder** — most active contributor across PRs, Verified Brews, and Discord
- **Best Cross-Book Contributor** — meaningful contributions across multiple books

Winners receive 1,000 BrewPoints, public recognition, and an iGulu premium ingredient set.

### Annual Awards (every December)
- **Master Brewers of the Year** — 10 contributors selected for cumulative impact
- Winners are listed on the title pages of the first printed edition

### Founding Contributors
The first 50 contributors whose Pull Requests are merged earn permanent **Founding Contributor** status — a tier that closes forever once filled.

### Translation Quest
The first contributor to lead translation of a new language earns the **Apostle of [Language]** lifetime title. Once a language is claimed, additional translators are welcomed as co-translators.

---

## Code of Conduct

This is a project where everyone — beginner brewer, experienced fermenter, food scientist, hobbyist — should feel welcome. See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) for behavioral expectations. Violations may result in PR closure, repository bans, or removal from contributor programs.

---

## Questions?

- **General questions**: open an Issue
- **CLA or licensing questions**: open an Issue labeled `cla-question`
- **Quick discussion**: join our Discord (link coming at public launch)
- **Private matters**: contact the maintainer via email `legal@igulu.com`

---

**Welcome to the Bible.** Your name might just end up in a book on someone's kitchen shelf in 2028.

— Shu Zhang, Project Maintainer
