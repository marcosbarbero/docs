---
layout: default
title: Dot Matrix Snake — Classic
permalink: /dot-matrix-snake/features/classic-mode/
---

# Classic

> An empty grid, your own best score, and a snake that gets faster the longer you last.

## What it does

Classic is the game everyone already knows. Swipe to steer, eat the fruit, do not hit a wall or your own tail. There is no level, no objective and no end — only how far you get.

## How it works

1. **PLAY → CLASSIC.**
2. Swipe anywhere on the panel to steer. There is no on-screen pad; the whole screen is the control.
3. Every fruit adds a segment and ten points.
4. **Every fifth fruit, the snake speeds up** — 220ms per step at the start, down to a floor of 90ms. The floor exists so it stays playable rather than becoming a reflex test.
5. Your best score is kept on the device and shown on the menu.

## The perfect game

If the snake fills every cell on the board there is nowhere left to put a fruit. That is a **win**, not a death, and it says so — the board is 12 × 16, so it takes 189 fruit.

## Second chances

Die close to your best and you are offered one revive per run. See [Second Chance]({{ site.baseurl }}/dot-matrix-snake/features/second-chance/).

## Known limits

- Scores are per-device. There is no leaderboard and no account.
- Turning is buffered two moves deep and validated when each step happens, not when you swipe — so a fast double-swipe cannot fold the snake back into its own neck.
