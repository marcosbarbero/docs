---
layout: default
title: VoiceScribe — AI Action Hub
permalink: /voice-scribe/features/action-hub/
---

# AI Action Hub

> Turn the commitments in a conversation into a checklist you can actually work — with due-date reminders and one-tap export — all on your phone.

## What it does

The Action Hub promotes the **Action Items** the AI extracts from a recording into an interactive, on-device **Task Matrix**: a checklist you can tick off, add your own tasks to, give due dates with local reminders, send to Apple Reminders, or share as Markdown.

The Task Matrix lives per recording — you'll find it both under **Action Items on the Insights tab** and inside a **capture's detail sheet**. Both show the same tasks (one on-device store), so a change in one place shows up in the other.

Everything runs on your device. No task, due date, or reminder leaves your phone.

## When to use it

- Pulling the to-dos out of a meeting and checking them off as you go.
- Setting a reminder for a commitment so it actually gets done.
- Handing a task to your real task manager (Reminders, Things, Todoist, Notion…) without retyping it.

## How it works

1. Record and transcribe something, then generate its **Insights** (Scribe Pass).
2. The **Task Matrix** appears with the extracted action items (with the responsible person when one was named). Tap a task to mark it complete; type in **Add Custom Task** to add your own.
3. Tap a task's **calendar** button to set a **due date** — VoiceScribe schedules a local reminder for it (you'll be asked for notification permission the first time).
4. Long-press a task and choose **Add to Reminders** to copy it into the native Reminders app, or use the **share** button to send the list as a Markdown checklist to any app.

## Free vs Premium

- **Free:** action items are part of Insights, which is a Scribe Pass feature.
- **Scribe Pass:** the interactive Task Matrix — completing and adding tasks, due-date reminders, one-tap Apple Reminders export, and Markdown share.

## Privacy

Everything stays on device. Tasks are stored in the app's local database (and sync through *your* private iCloud only if you've turned on iCloud Sync). Due-date reminders use the local notification system (a device-clock alert, no server); Apple Reminders export uses EventKit to write into *your* Reminders app; the share sheet hands a Markdown list to whatever app **you** pick. VoiceScribe makes no network request for any of this — there is no "sync to a server", and the "Data Not Collected" posture is unchanged.

## Known limits

- Tasks come from the AI's action items, so they're only as good as the extraction — review them, and add or edit as needed.
- Reminders and Apple Reminders export need their respective iOS permissions; if you decline, the task still lives in the app, just without the alert or the exported copy.
- A reminder fires on your device's clock for the due date you set; completing a task cancels its reminder.
