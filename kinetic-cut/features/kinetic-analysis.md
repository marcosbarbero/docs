---
layout: default
title: KineticCut — Kinetic Motion & Aesthetic Analysis
permalink: /kinetic-cut/features/kinetic-analysis/
---

# Kinetic Motion & Aesthetic Analysis

> KineticCut watches your footage for you — on your device — and pulls out the moments worth using.

## What it does

Point KineticCut at a video and it slices the long take into ~3-second segments, tagging each one with how the camera moved (a smooth pan, a tracking shot, a rapid whip-cut, a held shot), how strong the shot looks, and whether someone is looking at the camera. All of it runs on your device using Apple's Vision engine — no upload, no waiting on a server.

## When to use it

- You have a multi-minute clip and want the handful of usable B-roll moments without scrubbing.
- You're hunting for a specific kind of shot — a whip-pan, a clean tracking move — across a day's footage.
- You want the sharpest, best-composed frames surfaced automatically.

## How it works

1. Import a video on the **Clips** tab.
2. Open the **Timeline** tab — your clip appears, ready to analyse.
3. Tap **Analyze Track**.
4. KineticCut indexes the video and lists each ~3-second slice with its motion type, an aesthetic score, and a marker when someone is looking at the camera.

## Free vs Premium

- **Free:** full motion and aesthetic analysis of your imported videos.
- **Pro Creator Pass:** advanced motion-sorting presets (e.g. *isolate only whip-pans*) and automated expression-timestamp extraction.

## Privacy

Everything stays on device. KineticCut analyses your footage entirely with Apple's on-device Vision framework — no frames, scores, or timestamps ever leave your phone, and nothing is uploaded or stored off-device.

## Known limits

- Analysis samples a few frames per second rather than every frame, so events shorter than a fraction of a second may be missed — it's tuned for triage, not frame-exact editing.
- Camera-motion detection captures overall camera movement, not the motion of individual subjects within the frame.
- Expression detection currently flags a roughly front-facing face (gaze toward the camera); finer expression analysis comes later.
