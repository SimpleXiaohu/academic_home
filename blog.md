---
layout: page
title: "Technical Blog"
permalink: /blog/
---

Welcome to my technical blog. I collect experiments, solver internals, and practical notes here so future projects (and visitors) have a single place to follow along.

## How I Use This Space
- Short progress notes for solver research and verification tools.
- Longer writeups when a preprint, artifact, or release needs more context.
- Occasional tutorials so collaborators can reproduce a tricky setup.

## Draft Queue
1. Automata-guided pruning tricks for string constraints (planned).
2. Benchmarking pipeline for regex-dependent functions (in progress).
3. Lessons from the OSTRICH2 submission (notes coming soon).

## Publishing A New Entry
1. Create a Markdown file under `_posts/` named `YYYY-MM-DD-title.md`.
2. Add front matter similar to:
   ```
   ---
   layout: post
   title: "My String Solver Note"
   description: "What problem the entry solves"
   tags: [strings, smt, verification]
   ---
   ```
3. Write the content in Markdown (include figures or external links as needed).
4. Commit and deploy; the article will appear automatically on this page.

## Recent Highlights
- POPL 2022: transducers with priorities shaped the foundation for these notes.
- FMCAD 2025: OSTRICH2 release recap and follow-up experiments are in the pipeline.

Stay tuned—new posts will start appearing here soon.
