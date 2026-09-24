# Random Little Puzzles Landing Page

## Project Goal

Build the first public landing page for **RMLP — Random Mind-bending Little Puzzles**.

The site is the central home for a small, growing collection of free browser puzzles. Its immediate job is to:

1. Establish RMLP as a recognizable puzzle brand.
2. Help visitors choose and start a puzzle quickly.
3. Give visitors an obvious, friendly way to support the project.

This is currently a collection of three games, not a large gaming platform. Make the page feel finished and intentional without making it feel inflated.

## Source Documents and Assets

Treat these repository files as the primary project sources:

- `RMLP_LANDING_PAGE_BRIEF.md` — original product and implementation brief.
- `ChatGPT Image Sep 22, 2026, 01_30_17 PM.png` — broad visual inspiration only, not a page mockup.
- `rmlp-logo-mark.svg` — preferred compact brand mark and favicon source.
- `rmlp-logo-full.svg` — archival full wordmark containing an obsolete tagline.

The live games and their repositories are also design and product references:

- Word Web: <https://blendletan.github.io/WordWeb/> and <https://github.com/Blendletan/WordWeb>
- SpellSweep: <https://blendletan.github.io/SpellSweep/> and <https://github.com/Blendletan/SpellSweep>
- Beeline: <https://blendletan.github.io/Beeline/> and <https://github.com/Blendletan/Beeline>

When this file and the original brief differ because the live games clarified something, follow this file. In particular, use the corrected Word Web name and description below.

## Repository and Deployment Target

- GitHub repository: `Blendletan/RandomLittlePuzzles`
- Initial public URL: <https://blendletan.github.io/RandomLittlePuzzles/>
- Initial hosting: GitHub Pages
- Future domain: `randomlittlepuzzles.com`

The future custom-domain site may add accounts, OAuth, persistent user data, and other infrastructure. None of that is part of this version. Keep this implementation clean and portable, but do not build speculative infrastructure for a future phase.

## Current Scope

Create a static, responsive landing page with:

- a compact header;
- a compact hero;
- three prominent puzzle cards;
- a visible Ko-fi support section;
- a short About section;
- a compact footer;
- appropriate metadata and favicon;
- lightweight, privacy-conscious analytics consistent with the games;
- strong accessibility and responsive behavior.

Do not add:

- accounts, sign-in, OAuth, or databases;
- leaderboards, player counts, testimonials, or statistics;
- newsletter forms, blogs, or news systems;
- carousels, filtering, large menus, or modal dialogs;
- unnecessary frameworks or runtime dependencies;
- filler sections intended only to make the page look larger;
- fake screenshots or elaborate new game logos.

## Brand and Content Decisions

### Primary identity

Use the compact RMLP mark beside ordinary HTML text. The main brand language is:

- **RMLP**
- **Random Mind-bending Little Puzzles**
- **Free little puzzles for curious minds.**

The full name **Random Mind-bending Little Puzzles** must be the dominant hero headline and the first major message visitors see. Use **Free little puzzles for curious minds.** as the supporting tagline, not the primary heading.

### Contact

Visitors with questions or concerns must have a clear email contact:

- `robertparkinson@shaw.ca`

Use a normal `mailto:` link. Keep contact information visible in the About area and include a compact Contact link in the footer.

Never use the obsolete tagline **WORD PUZZLES, STRUCTURALLY** on the landing page. Do not destructively edit the original full-logo asset merely to remove it.

### Game names and approved card copy

Use these visible game names and descriptions:

#### Word Web

The visible product name is **Word Web**, with a space. `WordWeb` remains correct only when referring to the repository or URL.

> Connect three five-letter words by adding one-letter steps. Build the smallest web you can.

CTA: **Play Word Web →**

URL: <https://blendletan.github.io/WordWeb/>

The original brief's two-word description is inaccurate. The live game begins with three five-letter words and asks the player to connect all three into one web.

#### SpellSweep

> Trace words across a 5×5 board and cover every tile. Fewer words means a better score.

CTA: **Play SpellSweep →**

URL: <https://blendletan.github.io/SpellSweep/>

#### Beeline

> Build words across a hexagonal board and connect any pair of opposite edges.

CTA: **Play Beeline →**

URL: <https://blendletan.github.io/Beeline/>

### Shared game facts

The three games are daily browser puzzles. They share several useful series conventions:

- lower accepted-word counts are better;
- each puzzle has an exact `Perfect` score;
- first-time players receive an accessible tutorial;
- answer reveal and result sharing are available;
- each game displays the RMLP mark and an `RMLP PUZZLE` publisher label;
- each game uses Ko-fi support and lightweight GoatCounter analytics;
- each game is statically deployed and remains playable without a backend.

The landing page may reflect this shared identity, but it must not imply that every future RMLP game will necessarily use the same mechanics.

## Visual Direction

The landing page should feel:

- playful and intelligent;
- friendly and handmade;
- slightly whimsical;
- polished but not corporate;
- fast, clean, and easy to scan.

The landing page carries the shared RMLP identity while each game card preserves the personality of its game. Unify the collection; do not homogenize it.

### Page-level visual system

Use the established RMLP palette as the foundation:

- warm cream/paper: `#F6EFDD`;
- raised cream: `#FBF6EA`;
- dark brown/ink: `#2A2018`;
- muted brown: `#6E5D4C`;
- rule/border: `#C9B896`;
- reddish-orange brand accent: `#C1432B`;
- teal secondary accent: `#1F5C55`;
- gold accent: `#C99A2E`.

Muted green, blue, and brighter yellow may be added for the game-card illustrations, drawing from the supplied concept image. Use them as accents rather than saturated full-section backgrounds.

Preferred typography:

- display headings: Fraunces with a Georgia fallback;
- interface and body copy: Libre Franklin with system sans-serif fallbacks;
- small puzzle labels where appropriate: Courier Prime with a monospace fallback.

The site must remain readable if remote fonts fail to load.

### Game-card illustrations

Use small, static, spoiler-free illustrations rather than screenshots:

- **Word Web:** three or more teal word nodes connected by rust-coloured threads;
- **SpellSweep:** a compact square tile grid with a few clearly covered cells;
- **Beeline:** a compact hex field with a yellow/green path and, if useful, the existing bee identity.

Prefer inline or local SVG/CSS artwork. Do not import game runtime code, D3, puzzle data, or live daily boards. Do not reproduce the supplied landscape concept as a large page background.

## Required Page Structure

### Header

- Left: RMLP mark and `RMLP` text.
- Right: `Puzzles` and `Keep puzzles coming` same-page anchor links.
- Keep navigation compact. It does not need a mobile menu.

### Hero

- Heading: `Random Mind-bending Little Puzzles`.
- Tagline: `Free little puzzles for curious minds.`
- Supporting sentence: `A growing collection of original browser puzzles. No downloads, no accounts — just play.`
- Primary CTA: `Play a puzzle`, linking to the puzzle collection.
- Secondary CTA: `Help make more puzzles`, linking directly to Ko-fi.
- Keep the hero short enough that the puzzle collection begins within or near the first normal desktop viewport.
- A restrained path/node illustration may support the copy, but it must not dominate the page.

### Puzzle collection

- Heading: `Pick a puzzle`.
- Present the cards in this order: Word Web, SpellSweep, Beeline.
- On wide screens, show three cards in one row when comfortable.
- On smaller screens, stack them without cramped text or tiny controls.
- Make each card a single, large accessible link with a visibly styled CTA phrase inside it.
- Navigate to games in the same browser tab unless a concrete reason emerges to do otherwise.

### Support

- Heading: `Enjoying the puzzles?`
- Explain that RMLP is a small independent project and all games remain free.
- CTA: `Help make more puzzles ☕`.
- Link: <https://ko-fi.com/randomlittlepuzzles>
- Use a normal direct link. Do not add the floating Ko-fi widget to the landing page in the first release.

### About

- Heading: `What is RMLP?`
- Keep the section to roughly two short paragraphs.
- Mention words, logic, patterns, and other future puzzle types without pretending those games already exist.
- Include a visible questions-or-concerns email link to `robertparkinson@shaw.ca`.

### Footer

Include:

- RMLP mark;
- links to Word Web, SpellSweep, and Beeline;
- `Keep puzzles coming` Ko-fi link;
- Contact email link;
- compact RMLP/copyright text.

A GitHub link is optional and must not compete with the puzzle links.

## Technical Direction

Prefer the smallest sensible static implementation:

```text
index.html
styles.css
assets/
  rmlp-logo-mark.svg
  word-web-preview.svg
  spellsweep-preview.svg
  beeline-preview.svg
  social-preview.png
README.md
```

The exact asset filenames may change if a clearer organization emerges, but keep brand and preview assets local and organized.

Implementation rules:

- Use semantic HTML and plain CSS.
- Do not introduce a JavaScript framework, package manager, or build step.
- Avoid first-party JavaScript unless a concrete interaction truly requires it.
- Use relative paths for local assets.
- Use absolute production URLs for the three separately hosted games.
- Do not abstract three cards into an unnecessary component or data framework.
- Keep the canonical URL and deployment-specific metadata easy to change when the custom domain arrives.
- Avoid URL assumptions elsewhere in the markup and styles.

### Analytics

Use the existing `blendletan` GoatCounter site for a page view and a small set of constant, aggregate click events:

- Word Web card activation;
- SpellSweep card activation;
- Beeline card activation;
- Ko-fi support activation.

Do not include puzzle data, query contents, user-entered text, identifiers, or other personal/player data in analytics event names or payloads. Analytics failure or blocking must have no effect on page behavior.

## Accessibility and Responsive Requirements

- Use one clear `h1` and a sensible heading hierarchy.
- Use landmark elements such as `header`, `nav`, `main`, `section`, and `footer` appropriately.
- Ensure all links are usable by keyboard and have obvious focus states.
- Maintain sufficient colour contrast in normal, hover, focus, and visited states.
- Give decorative images empty alt text; give meaningful images concise useful alt text.
- Keep tap targets generous on phones.
- Do not rely on colour alone to distinguish the three cards or explain their illustrations.
- Avoid important content that moves or rearranges after loading.
- Respect `prefers-reduced-motion` for any nonessential transition or animation.
- Avoid horizontal overflow at narrow viewport widths.
- Check the site at approximately 1440px, 768px, and 390px widths.
- Verify that the site remains understandable with external fonts, analytics, or other third-party scripts blocked.

## Metadata and Social Presentation

Include:

- a descriptive page title;
- a concise meta description;
- canonical URL for the GitHub Pages release;
- Open Graph title, description, site name, URL, and image;
- appropriate theme colour;
- favicon derived from `rmlp-logo-mark.svg`.

Create a lightweight, properly sized social preview derived from the RMLP visual system. Do not ship the 2.2 MB concept PNG unchanged as the social image or a page background.

## Implementation Philosophy

Use this priority order:

**work → fast → pretty**

Prefer direct, readable code over architecture for its own sake. Build the strong first public hub described here, not the final infrastructure for a hypothetical future platform.

Before considering the landing page complete:

- test every external link;
- test keyboard navigation and focus visibility;
- test representative desktop, tablet, and phone layouts;
- confirm there is no horizontal overflow;
- confirm the page remains usable when third-party resources fail;
- verify the deployed GitHub Pages URL and all relative asset paths.

## Follow-up Outside This Repository

After the landing page is live, propose a separate, small update to each game adding an `All puzzles` link back to the landing page. Do not edit the three game repositories as part of this landing-page implementation unless the user explicitly asks for that coordinated follow-up.
