---
layout: default
title: Dot Matrix Snake — Campaign
permalink: /dot-matrix-snake/features/campaign-mode/
---

# Campaign

> Fifty levels with walls, corridors and pillar fields. Every one is verified solvable before it ships.

## What it does

Campaign gives the snake somewhere to be. Each level has a fixed layout of obstacles, a target number of fruit, and its own starting speed. Clear it and the next unlocks.

## How it works

1. **PLAY → CAMPAIGN**, then pick a level.
2. Levels you have cleared are filled in; the next one has a heavy border; locked ones are dimmed.
3. Eat the target number of fruit without hitting a wall, an obstacle or yourself.
4. Cleared levels can be replayed at any time — progress never goes backwards.

## The difficulty curve

Apple count and speed alone flatten out fast, so the second axis is the **shape** of the obstacles. The campaign moves through named bands:

| Levels | Shape |
|---|---|
| 1–2 | open board — learn to steer |
| 3–10 | single walls |
| 11–19 | mirrored block pairs |
| 20–29 | pillar fields, tightening |
| 30–39 | corridors with a single gap |
| 40–50 | mixed, densest |

## Every level is provably solvable

Levels are generated from a difficulty curve and then **checked** before they ship: a flood fill from the snake's starting cell must reach enough free space for the target, the start must not be walled in, and no free cell may be sealed off — because fruit could otherwise appear somewhere the snake can never reach.

The check runs again in continuous integration, written independently of the generator. Two implementations that must agree; if they ever disagree, the build fails. An impossible level 37 is the sort of thing a player finds, in a review.

## Known limits

- Fifty levels at present. The generator scales further and more are planned.
- Progress is per-device.
