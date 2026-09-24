# Random Little Puzzles

The public landing page for **RMLP — Random Mind-bending Little Puzzles**.

The first release is a dependency-free static site for GitHub Pages. It links to the three current daily puzzles:

- [Word Web](https://blendletan.github.io/WordWeb/)
- [SpellSweep](https://blendletan.github.io/SpellSweep/)
- [Beeline](https://blendletan.github.io/Beeline/)

## Run locally

Serve the repository root with any static HTTP server. For example:

```sh
python -m http.server 4173
```

Then open <http://127.0.0.1:4173/>.

There is no package install or build step.

## Deployment

The intended repository is `Blendletan/RandomLittlePuzzles`. GitHub Pages will publish the root of its `main` branch at:

<https://blendletan.github.io/RandomLittlePuzzles/>

See `AGENTS.md` for durable project rules and `MILESTONES.md` for the implementation and release roadmap.
