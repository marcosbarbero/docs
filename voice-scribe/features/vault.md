---
layout: default
title: VoiceScribe — Secure Memo Vault
permalink: /voice-scribe/features/vault/
---

# Secure Memo Vault

> Every recording you make is saved on your phone, searchable, tagged, and ready to export — and it never leaves the device.

## What it does

The Vault is your dashboard of recordings. Each memo you capture is stored locally with its transcript and details — length, file size, date, and whether it's been transcribed. You can search across everything, see the people, places, and organizations mentioned in a recording at a glance, and export any memo as a Markdown or text file.

Nothing is uploaded. The vault, the search, and the tagging all run on your device.

## When to use it

- Finding an earlier recording by what was said in it, not just its name.
- Reviewing which meetings have transcripts versus raw audio still to process.
- Pulling the key people or places out of a conversation without re-listening.
- Getting a transcript out of the app — into your notes, an email, or a document.

## How it works

1. Open the **Vault** tab. Your recordings appear under **Recent Captures**, newest first.
2. Each card shows the title, a **Transcribed** or **Raw Audio** badge, and the duration, size, and date. Recognized people, places, and organizations appear as small tags.
3. Type in **Search memos…** to filter by title or by anything said in the transcript.
4. **Tap a recording** to open its detail: play the audio back (play / pause with a progress bar), read the full transcript, jump to its **AI Insights**, and work its **Task Matrix**.
5. **Swipe a memo** for quick actions — from the trailing edge to **Rename** or **Delete**, from the leading edge to open its **AI Insights**. The **⋯** button (in the list or the detail) offers the same, plus **Export as Markdown** / **Export as Plain Text**.
6. Renaming opens a small dialog with the current title; type a new name and tap **Save**. A blank name is ignored. The new name persists across relaunch (and syncs if iCloud Sync is on).
7. Deleting asks you to confirm, then permanently removes the recording **and its audio** — there's no undo. If iCloud Sync is on, the deletion follows to your other devices.
8. Tap the microphone on the hero to jump straight to the **Record** tab and start a new recording.

## Free vs Premium

- **Free:** browse, search, **rename**, and **delete** memos, on-device entity tags, and plain-text copy.
- **Scribe Pass:** Markdown / text export.

## Privacy

Everything stays on device. VoiceScribe does not collect, transmit, or persist any data off your device. Recordings are stored only in the app's local storage, search and entity recognition run entirely on-device, and there is no account or cloud sync.

## Known limits

- Entity recognition (people, places, organizations) is best-effort and uses Apple's on-device language models; it won't catch everything.
- New recordings are named automatically from the start of what was said (a raw-audio recording falls back to a date-stamped name); you can rename any of them.
- Search matches the title and transcript text; a recording with no transcript is found by its title only.
- By default there is no cloud backup — memos live on the device they were recorded on. If you turn on **iCloud Sync** (off by default), your memos follow you across your own devices via your private iCloud; see the [iCloud Sync]({{ site.baseurl }}/voice-scribe/features/icloud-sync/) page.
