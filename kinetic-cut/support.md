---
layout: default
title: KineticCut — Support
permalink: /kinetic-cut/support/
---

# KineticCut Support

The fastest way to reach me is **[marcos@marcosbarbero.com](mailto:marcos@marcosbarbero.com)**. I'm a solo independent developer, so replies come from a human, not a queue.

## What to include

To help me triage faster:

- The app version + build, shown in **Settings → About → Version** (e.g. `1.0 (30)`).
- The iPhone model and iOS version (Settings → General → About).
- One screenshot of the unexpected behaviour, if it's a visual or layout problem.
- What you were doing — which step: importing on **Clips**, analysing on **Timeline**, or selecting/exporting on **Export**. If it's an export issue, the slice length you chose helps.

If you'd rather not send a screenshot, a one-sentence description of what you expected versus what happened is enough.

## Common questions

### Why can I only import 3 videos?

The free tier caps a session at three videos. The Pro Creator Pass lifts that to unlimited batch imports — tap **Go Pro** on the Export tab.

### Where did my analysed slices go?

Slices live in your current session. They're lightweight pointers back into the videos you imported, not copies — so if you start a brand-new import session, the previous slices are replaced. Export the ones you want before re-importing.

### Export says the source isn't available

A slice points back into the original video you imported. If that import session has ended, KineticCut can't trim the clip and will tell you so. Re-import the video and analyse it again to export from it.

### Can I cancel my subscription?

Yes, any time. **Settings → Subscription → How to cancel subscription** opens Apple's universal subscription-management page (`apps.apple.com/account/subscriptions`). Cancellation takes effect at the end of the current billing period.

### Can I get a refund?

Refunds for App Store purchases are handled by Apple, not by KineticCut. The process is at <https://reportaproblem.apple.com> — sign in with the Apple ID that made the purchase and pick KineticCut from the list.

## What I can't help with

- Apple account / billing issues. Apple handles all subscription billing, including refunds. I can't see your payment history, your Apple ID email, or your subscription status from the developer side — that's by design.
- What other apps do with your exported clips. KineticCut hands trimmed clips to the iOS share sheet; once they're in CapCut, Premiere, or Photos, that app's behaviour is its own.
- Custom feature requests on a deadline. Solo developer means a small bus factor — I prioritise bug fixes over feature requests when capacity is tight.

## Response time

Most emails get a reply within 48 hours on weekdays (Europe / Berlin time). Weekends I may be slower. If something is genuinely urgent — say, a crash that blocks every use of the app — flag the urgency in the subject line and I'll bump it.

## Privacy

This page exists purely to reach me. See the [Privacy Policy]({% raw %}{{ site.baseurl }}{% endraw %}/kinetic-cut/privacy-policy/) for the full posture.
