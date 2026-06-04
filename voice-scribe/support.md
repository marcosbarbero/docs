---
layout: default
title: VoiceScribe — Support
permalink: /voice-scribe/support/
---

# VoiceScribe Support

The fastest way to reach me is **[marcos@marcosbarbero.com](mailto:marcos@marcosbarbero.com)**. I'm a solo independent developer, so replies come from a human, not a queue.

## What to include

To help me triage faster:

- The app version + build, shown in **Settings → About → Version** (e.g. `1.0 (30)`).
- The iPhone model and iOS version (Settings → General → About).
- One screenshot of the unexpected behaviour, if it's a visual or layout problem.
- For a transcription or insight issue — the spoken language, roughly how long the recording was, and whether you were offline (airplane mode) at the time.

If you'd rather not send a screenshot, a one-sentence description of what you expected versus what happened is enough. Please **don't** send the recording or transcript itself unless I ask — your audio is private and stays on your device.

## Common questions

### Where are my recordings stored?

On your device, in VoiceScribe's private storage — they appear in the **Vault** tab, newest first. Nothing is uploaded by default. If you turn on **iCloud Sync** (off by default, in Settings), they also sync to your own iCloud so they appear on your other devices.

### Why is my transcript empty or inaccurate?

Transcription runs entirely on-device, so accuracy depends on Apple's on-device speech model for the spoken language, background noise, and microphone quality. A recording with no transcript is kept as **Raw Audio** — you can still rename, export, or delete it. Speaking clearly and reducing background noise gives the best results.

### How do I rename or delete a recording?

In the **Vault**, tap the **⋯** button on a memo. **Rename** opens a dialog for a new title; **Delete** asks you to confirm, then permanently removes the recording **and its audio** (there's no undo).

### Where are the AI summaries / highlights / action items?

The **Insights** features are generated on-device by Apple Intelligence. They require a device that supports Apple Intelligence with it enabled. On unsupported devices the rest of the app — recording, transcription, the vault — works normally.

### Does the app work offline?

Yes. Recording, transcription, and insights all run on-device and work in airplane mode. Only the optional iCloud Sync and the App Store paywall need a network connection.

### Can I cancel my subscription?

Yes, any time, via your Apple ID: **Settings → [your name] → Subscriptions**, or `apps.apple.com/account/subscriptions`. Cancellation takes effect at the end of the current billing period; Scribe Pass features stay available until then.

### Can I get a refund?

Refunds for App Store purchases are handled by Apple, not by VoiceScribe. The process is at <https://reportaproblem.apple.com> — sign in with the Apple ID that made the purchase and pick VoiceScribe from the list.

## What I can't help with

- Apple account / billing issues. Apple handles all subscription billing, including refunds. I can't see your payment history, your Apple ID email, or your subscription status from the developer side — that's by design.
- Recovering deleted recordings. Deletion is permanent and removes the audio; there is no server-side backup I could restore from. If iCloud Sync was on, deleting on one device deletes everywhere.
- Custom feature requests on a deadline. Solo developer means a small bus factor — I prioritise bug fixes over feature requests when capacity is tight.

## Response time

Most emails get a reply within 48 hours on weekdays (Europe / Berlin time). Weekends I may be slower. If something is genuinely urgent — say, a crash that blocks every recording — flag the urgency in the subject line and I'll bump it.

## Privacy

This page exists purely to reach me. VoiceScribe collects nothing and, by default, keeps everything on your device — see the [Privacy Policy]({{ site.baseurl }}/voice-scribe/privacy-policy/) for the full posture. If you email me, your message lives in my personal email account; I delete support correspondence once the issue is resolved unless it's useful as a future support note, in which case I anonymise any identifying detail first.
