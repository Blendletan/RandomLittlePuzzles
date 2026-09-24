# Random Little Puzzles Landing Page Milestones

## Purpose

This roadmap turns `RMLP_LANDING_PAGE_BRIEF.md`, the supplied brand assets, and the reviewed live games into a focused first release of the RMLP landing page.

Repository target:

- <https://github.com/Blendletan/RandomLittlePuzzles>

Initial public URL:

- <https://blendletan.github.io/RandomLittlePuzzles/>

Keep this file current as work proceeds. Mark items complete only after the implementation or verification actually occurred. When a decision changes, record the replacement rather than silently rewriting history.

## Current Project State

As of September 23, 2026, this folder contains:

- the original landing-page brief;
- the compact RMLP logo mark;
- the older full RMLP wordmark;
- a broad visual-concept image;
- this roadmap and `AGENTS.md`;
- a complete first-pass static landing page and local SVG card artwork.

The landing page is implemented and locally verified. The optimized social-preview image and its sharing metadata are complete. The folder is not yet a Git repository, and GitHub Pages release work remains open.

The three live games and their source repositories were reviewed before this roadmap was written. Important findings are recorded in `AGENTS.md`, including the corrected **Word Web** display name and its three-starting-word description.

## Confirmed Decisions

- [x] Use `RandomLittlePuzzles` as the GitHub repository and Pages project name.
- [x] Deploy initially at `https://blendletan.github.io/RandomLittlePuzzles/`.
- [x] Keep the first version static and dependency-free.
- [x] Use the compact RMLP mark with HTML text instead of the obsolete full-logo tagline.
- [x] Use the warm RMLP identity for the page while preserving each game's individual personality.
- [x] Use spoiler-free miniature illustrations rather than game screenshots.
- [x] Use **Word Web** as the visible product name.
- [x] Describe Word Web accurately as connecting three five-letter starting words.
- [x] Keep the support request visible in the page and link directly to Ko-fi.
- [x] Do not use the floating Ko-fi widget on the first landing-page release.
- [x] Use the existing privacy-conscious GoatCounter approach for page and CTA events.
- [x] Treat backlinks from the three games as a separate follow-up after launch.
- [x] Make `Random Mind-bending Little Puzzles` the dominant hero headline.
- [x] Publish `robertparkinson@shaw.ca` as the questions-or-concerns contact.
- [x] Use `Keep puzzles coming` for the header and footer Ko-fi navigation instead of the ambiguous standalone word `Support`.
- [x] Use `Help make more puzzles` for the Ko-fi calls to action.

## Milestone 0: Planning Baseline

- [x] Review the original landing-page brief.
- [x] Inspect the supplied concept image and SVG logo assets.
- [x] Review the live Word Web, SpellSweep, and Beeline experiences.
- [x] Review the three source repositories for game rules, visual conventions, deployment patterns, accessibility, support, and analytics.
- [x] Agree on the landing-page creative and technical direction.
- [x] Record durable project instructions in `AGENTS.md`.
- [x] Record the implementation roadmap in this file.

Completion criteria: a future work session can understand the product, visual direction, approved copy, technical constraints, deployment target, and release sequence from the repository itself. Complete.

## Milestone 1: Static Foundation

- [x] Create a semantic `index.html` with header, main content, and footer landmarks.
- [x] Create `styles.css` with page-level RMLP colour, typography, spacing, radius, and focus tokens.
- [x] Copy or organize the compact logo mark under the final asset structure without destructively changing the supplied source.
- [x] Add the compact header with working `Puzzles` and `Keep puzzles coming` anchor links.
- [x] Add the compact hero with the approved name, tagline, supporting sentence, and two CTAs.
- [x] Add placeholder-free structural sections for puzzles, support, About, and footer.
- [x] Ensure all local asset paths are relative and compatible with the `/RandomLittlePuzzles/` GitHub Pages base path.
- [x] Add a short `README.md` covering local serving and deployment.
- [x] Confirm the page works from a simple static HTTP server with no build step.

Implementation result (September 23, 2026): the complete semantic page shell, local asset structure, base design system, content sections, and static-server workflow are in place. The page requires no first-party JavaScript or build step.

Completion criteria: the complete information architecture is present, usable without JavaScript, and ready for visual styling. Complete.

## Milestone 2: Puzzle Collection and Visual Identity

- [x] Build the Word Web card with the approved name, description, CTA, and link.
- [x] Build the SpellSweep card with the approved description, CTA, and link.
- [x] Build the Beeline card with the approved description, CTA, and link.
- [x] Make each card one large semantic link while retaining an obvious CTA phrase.
- [x] Create a small, spoiler-free Word Web node-and-thread illustration.
- [x] Create a small, spoiler-free SpellSweep tile-grid illustration.
- [x] Create a small, spoiler-free Beeline hex-path illustration.
- [x] Give the cards distinct accents while keeping typography, spacing, borders, and interaction states recognizably RMLP.
- [x] Keep the hero compact enough that the puzzle collection begins within or near a normal desktop viewport.
- [x] Add only restrained hover/focus motion and disable nonessential motion under `prefers-reduced-motion`.

Implementation result (September 23, 2026): all three cards are implemented as large accessible links with custom local SVG artwork. Desktop and narrow-screen visual checks confirm that the shared card system remains cohesive while the game geometry and colours stay distinct.

Completion criteria: a visitor can immediately recognize the RMLP brand, understand the three different games, and start any puzzle without navigating through extra content. Complete.

## Milestone 3: Support, About, and Footer

- [x] Add the visible `Enjoying the puzzles?` support section.
- [x] State clearly that RMLP is independent and that all games remain free.
- [x] Add the direct `Help make more puzzles ☕` Ko-fi link.
- [x] Add the short `What is RMLP?` section without turning it into a long manifesto.
- [x] Add footer links to Word Web, SpellSweep, Beeline, and `Keep puzzles coming`.
- [x] Add the compact RMLP mark and copyright text to the footer.
- [x] Ensure the support treatment is noticeable without behaving like an interruption.
- [x] Add a visible questions-or-concerns email link in the About section.
- [x] Add a compact Contact link in the footer.

Implementation result (September 23, 2026): the visible gold support panel, concise About copy, questions-or-concerns email link, and compact dark footer are implemented and visually verified on desktop.

Completion criteria: support is easy to find, the project is briefly explained, and the footer offers a useful compact navigation endpoint. Complete.

## Milestone 4: Metadata, Analytics, and Accessibility

- [x] Add the production page title and meta description.
- [x] Add the canonical GitHub Pages URL.
- [x] Add Open Graph title, description, site name, URL, and image metadata.
- [x] Add an appropriate theme colour.
- [x] Use the compact RMLP mark as the favicon.
- [x] Create and optimize a correctly sized social-preview image rather than shipping the large concept image unchanged.
- [x] Add the existing `blendletan` GoatCounter page-view integration.
- [x] Add constant aggregate click events for the three game cards and the Ko-fi link.
- [x] Confirm that analytics sends no puzzle, player-entered, or personal data.
- [x] Confirm that blocking or suppressing analytics does not affect navigation or layout.
- [x] Verify the heading hierarchy and landmark structure.
- [x] Verify every interactive element by keyboard.
- [x] Verify visible focus styles and adequate colour contrast.
- [x] Verify meaningful versus decorative image alternatives.
- [x] Verify that the page does not rely on colour alone.

Completion criteria: the page is discoverable, shareable, keyboard-friendly, and privacy-conscious without adding application infrastructure.

Implementation result (September 23, 2026): `assets/social-preview.png` is a 1200×630 optimized PNG, and Open Graph plus summary-card metadata reference its production URL. Browser testing traversed all 17 interactive links in order and confirmed a visible focus ring on each. The page remains usable when GoatCounter declines to count the local origin.

## Milestone 5: Responsive and Browser Verification

- [x] Verify the desktop layout at approximately 1440px wide.
- [x] Verify the tablet layout at approximately 768px wide.
- [x] Verify the phone layout at approximately 390px wide.
- [x] Verify a narrower phone layout near 320–340px if practical.
- [x] Confirm that cards form a comfortable row on wide screens and stack cleanly on small screens.
- [x] Confirm there is no horizontal overflow.
- [x] Confirm header branding and navigation never become cramped.
- [x] Confirm tap targets remain generous on touch-sized layouts.
- [x] Confirm the hero does not push all puzzle choices below the fold on a normal desktop display.
- [x] Test every game link and the Ko-fi link.
- [x] Test with remote fonts blocked and confirm readable fallbacks.
- [x] Test with analytics and other third-party scripts blocked.
- [x] Check the browser console for errors and avoid shipping known warnings.
- [ ] Check the page in at least two available modern browser engines when practical.

Completion criteria: the landing page remains attractive, readable, and fully usable across the intended viewport range and normal third-party failure conditions.

Verification result (September 23, 2026): Word Web, SpellSweep, and Beeline each returned HTTP 200, and the Ko-fi destination opened to the correct RMLP profile in a real browser. Removing the remote font requests left the page readable and free of horizontal overflow at the narrow test viewport. The console contained no errors; GoatCounter's expected `localhost` non-counting warning was the only warning. A second browser engine was not available in the current test environment and remains an optional production smoke check.

## Milestone 6: Git and GitHub Pages Release

- [ ] Initialize this folder as a Git repository using `main` as the primary branch.
- [ ] Review the complete initial file set and exclude local-only or unnecessary assets.
- [ ] Create the `Blendletan/RandomLittlePuzzles` GitHub repository.
- [ ] Add it as the `origin` remote.
- [ ] Commit the reviewed landing-page implementation.
- [ ] Push `main` to GitHub.
- [ ] Configure GitHub Pages to publish the static site from the repository root on `main`.
- [ ] Verify `https://blendletan.github.io/RandomLittlePuzzles/` loads successfully.
- [ ] Verify all CSS, images, favicon, and social metadata use valid deployed paths.
- [ ] Verify all three game links and Ko-fi from the deployed page.
- [ ] Verify GoatCounter page views and constant CTA events on the deployed page.
- [ ] Perform a final desktop and phone-sized smoke test against the production URL.

Completion criteria: the public URL is live, all required assets and links work, and the first RMLP hub is ready to share.

## Milestone 7: Post-launch Ecosystem Follow-up

This milestone changes the three game repositories and therefore requires a separate explicit request before implementation.

- [ ] Add a small `All puzzles` link from Word Web to the RMLP landing page.
- [ ] Replace or complement Word Web's direct `More puzzles: SpellSweep` link with the collection link.
- [ ] Add an `All puzzles` link from SpellSweep to the RMLP landing page.
- [ ] Add an `All puzzles` link from Beeline to the RMLP landing page.
- [ ] Keep each game's existing visual identity and compact footer treatment.
- [ ] Add only constant, aggregate analytics for the new navigation links if consistent with each game's current policy.
- [ ] Verify the full navigation loop from landing page to every game and back.

Completion criteria: RMLP functions as a true two-way hub rather than only a page that sends traffic outward.

## Explicit Non-goals for the First Release

- Custom-domain migration.
- User accounts, OAuth, or persistent cross-game profiles.
- Backend services, databases, or APIs.
- Shared game runtime packages or a general puzzle framework.
- Dynamic game feeds or daily-puzzle previews.
- Search, filtering, categories, or collection pagination.
- A CMS, blog, newsletter, or announcement system.
- Elaborate animation or a full-page reproduction of the concept landscape.

## Starting Point for the Next Work Session

Begin Milestone 6 by initializing the repository, reviewing the final release file set, and creating the `Blendletan/RandomLittlePuzzles` GitHub repository. Then publish from `main`, verify the production URL and assets, and complete the production smoke checks.
