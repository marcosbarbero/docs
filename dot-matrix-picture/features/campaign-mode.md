---
layout: default
title: Dot Matrix Picture — Fifty puzzles
permalink: /dot-matrix-picture/features/campaign-mode/
---

# Fifty puzzles

Fifty nonograms, growing from five by five to twelve by twelve across six difficulty bands. The early boards are small enough that a whole row falls out of a single number; the last ones drop the symmetry that makes a grid easy to read and need the whole board at once.

## Proved, not sampled

Every level is run through a solver before it ships. The solver propagates constraints and never branches — it will not guess, so anything it cannot finish is a puzzle that *requires* a guess, and those are thrown away by the generator rather than shipped.

The check runs again over the committed campaign file, not the generator's output, so what was proved and what is installed cannot be two different things.

## Three lives

A wrong cell costs a life. A nonogram is reasoned out over minutes, so ending a long board on a single mis-tap would be a punishment out of proportion to the mistake.
