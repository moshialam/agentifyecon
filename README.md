# LLMs for Economists

A short Quarto site that gets economics-department colleagues started with
agentic coding using Claude Code. Big-picture orientation, then example-based
guidance grounded in things economists actually do (LaTeX papers, Stata/R/
Python/Matlab/Julia, replication packages, refereeing, teaching).

## Build locally

```bash
quarto preview     # live-reloading dev server
quarto render      # build the static site into docs/
touch docs/.nojekyll   # re-create the GH Pages marker (quarto wipes it)
```

## Deploy

The site renders to `docs/`. Push to GitHub and enable Pages on the `main`
branch, `/docs` folder. The empty `docs/.nojekyll` file tells GitHub Pages
to serve the rendered HTML directly instead of running it through Jekyll —
so re-touch it after each `quarto render` (or wrap both commands in a
small shell function).
