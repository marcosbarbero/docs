---
layout: default
title: VoiceScribe — iCloud Sync
permalink: /voice-scribe/features/icloud-sync/
---

# iCloud Sync

> Keep your recordings, transcripts, and insights on all your devices — through your own private iCloud, off by default, with nothing ever sent to us.

## What it does

iCloud Sync lets the recordings you make on one device show up on your other devices signed into the same iCloud account — an iPhone recording waiting for you on your iPad. It is **off by default**. When you leave it off, VoiceScribe behaves exactly as it always has: everything stays on the single device that made it, and nothing leaves the phone.

When you turn it on, your memos, transcripts, AI insights, and the recording audio itself sync through **your own private iCloud**. That data lives in your personal iCloud account — it is never sent to a VoiceScribe server (there are none), the developer cannot read it, and there is no account to create.

## When to use it

- You record on your iPhone but review and edit on your iPad.
- You want your library to survive setting up a new device.
- You want an off-device copy of your recordings without handing them to a third-party cloud.

Leave it off if you prefer the strongest posture — a single device that holds the only copy.

## How it works

1. Open **Settings** (the gear in the Vault header).
2. Find **iCloud Sync**. It is **off** by default.
3. Turn it on. New and existing memos — including their audio — begin syncing to your private iCloud.
4. On another device signed into the **same iCloud account**, install VoiceScribe and turn on iCloud Sync there too. Your library appears.
5. Turn it off at any time to go back to local-only storage on that device.

## Free vs Premium

- **Free:** iCloud Sync is available — it is **not** behind Scribe Pass. Your subscription and your content both follow you across your devices without paying for sync.
- **Scribe Pass:** unchanged by sync. (Scribe Pass gates unlimited continuous recording, AI insight generation, and Markdown/text export — see [Scribe Pass]({{ site.baseurl }}/voice-scribe/features/scribe-pass/).)

## Privacy

> ⚠️ This is the one feature that, **when you enable it**, moves content off the phone — to *your own* iCloud, never to us.

With iCloud Sync **off** (the default), everything stays on device: VoiceScribe collects, transmits, and persists nothing off your phone. With it **on**, your content syncs only to your private iCloud (Apple's iCloud/CloudKit private database). It is not collected by VoiceScribe, not accessible to the developer, and not shared with anyone; Apple's handling of iCloud data is governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). The app's privacy manifest remains **Data Not Collected** because a user's private iCloud database is not developer data collection.

## Known limits

- Both devices must be signed into the **same iCloud account** with iCloud Drive available.
- Sync needs a network connection and an active iCloud account; it does not work in airplane mode (recording and transcription still do).
- There is no app account and no way to share a library with another *person* — sync is across your own devices only.
- Conflicts use last-writer-wins; editing the same memo on two offline devices keeps the most recent save.
