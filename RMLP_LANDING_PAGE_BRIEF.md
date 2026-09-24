# RMLP Landing Page — Codex Implementation Brief

## Project

Build the first public landing page for:

**RMLP — Random Mind-bending Little Puzzles**

This is the central hub for a growing collection of free browser puzzle games.

For **this first version**, the site will still be hosted on **GitHub Pages**.

A later phase will move the project to **randomlittlepuzzles.com** and will likely add much more substantial infrastructure, including **user accounts, OAuth, persistent user data, and other site-level features**.

Do **not** build any of that future infrastructure now. However, avoid needless decisions that would make the later migration harder. Keep the landing page clean, modular, and easy to evolve.

---

## Files I am providing

You will also receive these three branding files:

1. `ChatGPT Image Sep 22, 2026, 01_30_17 PM.png`
   - A broad visual branding concept for RMLP.
   - Use it as **visual inspiration**, not as a page mockup that must be copied literally.

2. `rmlp-logo-full.svg`
   - Existing full RMLP wordmark.
   - Important: it contains the old tagline **“WORD PUZZLES, STRUCTURALLY”**.
   - Do **not** use that old tagline on the new landing page.
   - Do not edit the original asset destructively unless there is a strong reason.

3. `rmlp-logo-mark.svg`
   - Existing compact RMLP mark.
   - This is the preferred reusable brand mark for the header, favicon, footer, and other compact uses.

The compact logo mark plus ordinary HTML text is probably the best main branding treatment for this site.

---

## Main goals

The page should do three things very well:

1. Establish **RMLP** as a recognizable puzzle brand.
2. Get visitors into one of the games quickly.
3. Give people who enjoy the games an obvious way to support the project.

This is currently a collection of **three games**. Do not pretend it is already a giant gaming platform.

The page should feel intentional and finished, but not overbuilt.

---

## Current games

The landing page must prominently link to these three games.

### WordWeb

URL:

`https://blendletan.github.io/WordWeb/`

Suggested short description:

> Connect two words by changing one letter at a time. Find the shortest path you can.

CTA:

**Play WordWeb →**

---

### SpellSweep

URL:

`https://blendletan.github.io/SpellSweep/`

Suggested short description:

> Find words across the board and cover every tile. The fewer words you use, the better.

CTA:

**Play SpellSweep →**

---

### Beeline

URL:

`https://blendletan.github.io/Beeline/`

Suggested short description:

> Build word paths across a hexagonal board and connect opposite sides.

CTA:

**Play Beeline →**

---

## Hosting and implementation scope

For tonight:

- Deploy as a static site on **GitHub Pages**.
- No backend.
- No accounts.
- No OAuth.
- No database.
- No API layer.
- No fake placeholders for future account functionality.

Keep the implementation simple enough to deploy immediately.

At the same time:

- Keep assets organized.
- Keep page sections reasonably modular.
- Avoid unnecessary coupling to one permanent URL structure.
- Use relative asset paths where appropriate.
- Do not design the HTML/CSS in a way that assumes this will always remain a tiny one-page GitHub Pages project.

The future `randomlittlepuzzles.com` migration is **not part of this task**.

---

## Visual direction

Use the supplied branding as the starting point.

The site should feel:

- playful
- intelligent
- friendly
- independent / handmade
- slightly whimsical
- polished but not corporate
- inviting to people who simply want to try a puzzle

The large branding concept image suggests useful ideas:

- exploration
- paths
- hills / journeys
- puzzle pieces
- nodes and connections
- warm, cheerful colours
- a sense that there are different kinds of puzzles to discover

Use those ideas subtly.

Do **not** reproduce the whole illustration as a giant webpage background.

The real page should remain clean, readable, fast, and focused on the games.

### Existing logo palette

The supplied SVG assets already establish a useful palette:

- warm cream
- dark brown / near-black
- muted reddish-orange accent

The broader branding concept also introduces yellow, green, and blue.

Use these colours with restraint rather than turning every section into a different saturated colour block.

---

## Brand treatment

Preferred approach:

Use `rmlp-logo-mark.svg` beside HTML text such as:

**RMLP**

**Random Mind-bending Little Puzzles**

The main tagline should be:

**Free little puzzles for curious minds.**

Do **not** use:

**WORD PUZZLES, STRUCTURALLY**

That tagline belongs to an earlier branding direction and is too narrow for the broader RMLP collection.

The current games are word-heavy, but RMLP is intended to expand into logic, structural, pattern, and other puzzle types.

---

## Page structure

### 1. Header

Keep the header simple.

Left side:

- RMLP mark
- RMLP name

Right side:

- **Puzzles**
- **Support**

These may be anchor links to sections on the same page.

Do not add elaborate navigation yet.

---

### 2. Hero

Keep the hero relatively compact.

The user should be able to understand the site quickly and begin seeing the games without scrolling through an enormous promotional banner.

Suggested content:

**Random Mind-bending Little Puzzles**

**Free little puzzles for curious minds.**

Optional supporting sentence:

> A growing collection of original browser puzzles. No downloads, no accounts — just play.

Primary CTA:

**Play a puzzle**

This should scroll to the puzzle section.

Secondary CTA:

**Support more puzzles**

This should link to the RMLP Ko-fi page.

Do not make the hero so tall that the actual games disappear below the fold on a normal desktop display.

---

## 3. Puzzle collection

This is the most important section.

Suggested heading:

**Pick a puzzle**

Create three substantial game cards:

- WordWeb
- SpellSweep
- Beeline

The cards should be visually distinct enough to scan quickly while clearly belonging to the same RMLP site.

Make the entire card clickable if practical, while also keeping an obvious Play CTA.

### Card content

Each card should contain:

- game name
- short description
- obvious Play CTA
- a small visual treatment appropriate to that game

If suitable game screenshots or existing game-specific assets are already available in the repository, feel free to use them.

If not, make strong text-first cards rather than inventing fake screenshots or spending excessive time creating new artwork.

Do not create elaborate new game logos for this first pass.

---

## 4. Support / donation section

This needs to be a real, visible section.

It should not be hidden only in the footer.

Suggested copy:

### Enjoying the puzzles?

> RMLP is a small independent puzzle project. If you'd like to help keep the puzzles coming, you can support the project on Ko-fi.

Prominent CTA:

**Support more puzzles ☕**

Ko-fi account:

`https://ko-fi.com/randomlittlepuzzles`

The donation request should be noticeable without being annoying.

All games remain free.

A floating Ko-fi widget may be added later or elsewhere, but this visible in-page CTA should work on its own.

---

## 5. About section

Keep this brief.

Suggested heading:

**What is RMLP?**

Suggested copy:

> Random Mind-bending Little Puzzles is a growing collection of free browser puzzles — words, logic, patterns, and whatever else seems interesting.

> More puzzles are on the way.

This is not intended to be a long founder story or manifesto.

---

## 6. Footer

Keep the footer compact.

Include:

- RMLP mark
- WordWeb
- SpellSweep
- Beeline
- Support
- RMLP / copyright text

If appropriate, a GitHub link can also be included, but it should not compete with the puzzle links.

---

## Responsive behaviour

The page must work well on:

- desktop
- tablet
- phone

On desktop:

- three puzzle cards may sit in one row if they fit comfortably

On smaller screens:

- stack the cards vertically
- preserve generous tap targets
- avoid tiny text
- make sure the logo and title do not become cramped

The page should remain pleasant and usable without requiring pixel-perfect desktop dimensions.

---

## Accessibility and technical quality

Please include:

- semantic HTML
- sensible heading hierarchy
- accessible links and buttons
- keyboard usability
- visible focus states
- useful alt text where appropriate
- sufficient colour contrast
- responsive layout
- fast loading
- minimal dependencies
- good page title and meta description
- favicon using the RMLP mark if practical

If animation is used:

- keep it subtle
- do not make important content move around
- respect `prefers-reduced-motion`

No animation is required.

---

## Things to avoid

Do not add:

- user accounts
- sign-in buttons
- OAuth placeholders
- leaderboards
- fake player counts
- fake testimonials
- fake statistics
- a news/blog system
- a newsletter signup
- a carousel
- giant modal dialogs
- complicated menus
- elaborate filtering
- unnecessary frameworks
- excessive animation
- excessive gradients/glow effects
- generic SaaS-style feature sections
- large amounts of filler content

Do not build features merely to make the page look busier.

---

## Design hierarchy

A visitor should understand the page in roughly this order:

**This is RMLP**

→

**Here are the puzzles**

→

**Pick one and play**

→

**If you enjoyed them, support the project**

That hierarchy matters more than adding more sections.

---

## Implementation philosophy

For this first pass:

**work → fast → pretty**

Produce a clean, functional, attractive first version that can be deployed to GitHub Pages tonight.

Do not spend excessive time solving hypothetical future requirements.

At the same time, keep the implementation sane enough that this landing page can later become part of the larger `randomlittlepuzzles.com` site rather than needing to be completely untangled.

The goal is a strong first public hub, not the final architecture for the entire future RMLP platform.
