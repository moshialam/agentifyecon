# LLMs for Economists

A short Quarto site that gets economics-department colleagues started with
agentic coding using Claude Code. Big-picture orientation, then example-based
guidance grounded in things economists actually do (LaTeX papers, Stata/R/
Python/Matlab/Julia, replication packages, refereeing, teaching).

## Build locally

```bash
quarto preview     # live-reloading dev server
quarto render      # build the static site into docs/
```

## Deploy

The site renders to `docs/`. Push to GitHub and enable Pages on the `main`
branch, `/docs` folder.
