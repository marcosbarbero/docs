---
layout: default
title: PanoSlice — Support
permalink: /pano-slicer/support/
---

# PanoSlice Support

The fastest way to reach me is **[marcos@marcosbarbero.com](mailto:marcos@marcosbarbero.com)**. I'm a solo independent developer, so replies come from a human, not a queue.

## What to include

To help me triage faster:

- The app version + build, shown in **Settings → About → Version** (e.g. `1.0 (30)`).
- The iPhone model and iOS version (Settings → General → About).
- One screenshot of the unexpected behaviour, if it's a visual or layout problem.
- For export issues — the slicing mode (Carousel or Grid), the spec you chose (e.g. `3 tiles at 3:4`), and whether the source photo was a panorama, portrait, or square.

If you'd rather not send a screenshot, a one-sentence description of what you expected versus what happened is enough.

## Common questions

### Where are the sliced tiles?

PanoSlice writes tiles directly to your iPhone's camera roll. Open the Photos app and look at the **Recents** album. The tiles land consecutively in the order PanoSlice slices them.

If nothing appears in Photos after an export, check **Settings → PanoSlice → Photos**. The permission needs to be set to either **Add Photos Only** or **All Photos**. "Selected Photos" works for *reading* but blocks *writing* — that's iOS's design.

### How do I jump to Photos or Instagram after exporting?

The success overlay gives you **Photos** and **Instagram** shortcut pills below the "Saved to your camera roll" headline. Tap either to launch the destination app directly — Photos lands you on the camera roll so you can confirm the tiles; Instagram lands you on its library picker so you can start a new post right away. The Instagram shortcut only appears if Instagram is installed on the device.

### Why is there a "PanoSlice" watermark on my tiles?

The Free tier writes a small `PanoSlice` chip in the bottom-right of each tile. Premium removes it on every export. See the **Subscription** section of the in-app **Settings** sheet to upgrade.

If you upgraded but the watermark is still showing, tap **Settings → Subscription → Restore purchases** — that re-fetches your entitlement from Apple's StoreKit. If the banner still says "Free" after a successful restore, send me an email with the date and Apple ID country of purchase.

### Why won't a 10-tile carousel export?

Free is capped at 2- or 3-tile carousels. Tapping Export on a 4–10 tile spec while on Free opens the paywall instead of exporting. After purchase, tap Export again and the tiles write.

### Why does my image look cropped in the workspace?

The slicing grid sits inside the image's visible fit-rect (see [the privacy policy → on-device storage]({{ site.baseurl }}/pano-slicer/privacy-policy/) if you're curious why everything is local). To compose, pinch to zoom in and drag to pan — the grid is fixed, the image moves underneath. Double-tap to reset.

### Can I cancel my subscription?

Yes, any time. **Settings → Subscription → How to cancel subscription** opens Apple's universal subscription-management page (`apps.apple.com/account/subscriptions`). Cancellation takes effect at the end of the current billing period; Premium features stay available until then.

### Can I get a refund?

Refunds for App Store purchases are handled by Apple, not by PanoSlice. The process is at <https://reportaproblem.apple.com> — sign in with the Apple ID that made the purchase and pick PanoSlice from the list.

## What I can't help with

- Apple account / billing issues. Apple handles all subscription billing, including refunds. I can't see your payment history, your Apple ID email, or your subscription status from the developer side — that's by design.
- Instagram or third-party app behaviour. PanoSlice writes tiles to your camera roll; from there, whichever app you upload them to (Instagram, Pinterest, Threads) decides how to render. If a destination crops the tile, that's the destination's call, not PanoSlice's.
- Custom feature requests on a deadline. Solo developer means a small bus factor — I prioritise bug fixes over feature requests when capacity is tight.

## Response time

Most emails get a reply within 48 hours on weekdays (Europe / Berlin time). Weekends I may be slower. If something is genuinely urgent — say, a crash that blocks every export on every photo — flag the urgency in the subject line and I'll bump it.

## Privacy

This page exists purely to reach me. PanoSlice itself collects nothing — see the [Privacy Policy]({{ site.baseurl }}/pano-slicer/privacy-policy/) for the full posture. If you email me, your message is stored in my personal email account; I delete support correspondence after the issue is resolved unless the conversation is useful as a future support article (in which case I'd anonymise any identifying detail first).
