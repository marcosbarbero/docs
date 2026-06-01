---
layout: default
title: PanoSlice — Privacy Policy
permalink: /pano-slicer/privacy-policy/
---

# PanoSlice Privacy Policy

**Effective date:** 2026-06-01
**Last updated:** 2026-06-01

This privacy policy explains how PanoSlice ("PanoSlice", "the app", "we", "I" — PanoSlice is published by Marcos Barbero, a solo independent developer) handles your information. PanoSlice is an iOS application distributed via the Apple App Store.

The short version: PanoSlice collects nothing, transmits nothing, and has no servers. The long version follows.

## 1. Information collected

**PanoSlice does not collect, store, transmit, or share any personally identifiable information.**

Specifically, PanoSlice does not collect:

- Your name, email address, phone number, postal address, or Apple ID.
- Your location, GPS coordinates, or IP address.
- Your contacts, calendar entries, or messages.
- Your device identifier (IDFA / IDFV), advertising ID, or any cross-app identifier.
- Analytics on which buttons you tap, which features you use, or how long you spend in the app.
- Crash reports (PanoSlice does not embed any third-party crash reporting SDK; Apple's first-party crash reporting can be enabled or disabled by you in your device's Settings → Privacy & Security → Analytics & Improvements).

## 2. Access to your data

PanoSlice asks for two iOS permissions:

- **Photo Library (read).** When you tap "Choose a photo" or a mode tile, iOS presents the system Photos picker. The picker — not PanoSlice — decides which photos to show. PanoSlice receives only the photo(s) you explicitly select. If you use iOS's Limited Photo Library Access, PanoSlice sees only the subset you have authorised; it cannot enumerate or read photos outside that subset.
- **Photo Library (add only).** When you tap **Export carousel** or **Save to camera roll**, PanoSlice writes the sliced tiles back to your camera roll. The add-only permission does not grant PanoSlice the ability to read previously-saved photos.

Both permissions are revocable at any time via iOS Settings → PanoSlice.

## 3. On-device storage

PanoSlice stores the following data on your device only:

- Your chosen export format (JPEG or PNG) in `UserDefaults` so the Settings sheet picker remembers your preference between launches. This is in the app's private container and is removed when the app is uninstalled.
- Temporary tile files during export, in the app sandbox's `tmp/` directory. These are deleted by iOS automatically; they never leave the sandbox.

PanoSlice does **not** maintain a database, history log, or exportable settings file. Nothing PanoSlice writes ever leaves your device.

## 4. Subscriptions

PanoSlice offers an optional **Premium** subscription (monthly or annual) through the Apple App Store. Subscriptions are handled entirely by Apple's StoreKit infrastructure:

- The payment transaction is between you and Apple. PanoSlice never sees your payment method, billing address, or Apple ID email.
- Your subscription status is resolved on-device by Apple's StoreKit; PanoSlice asks StoreKit "is the current user Premium?" and StoreKit answers locally. PanoSlice never queries a separate backend to verify your subscription.
- **Restore Purchases** in the Settings sheet calls Apple's StoreKit `AppTransaction.refresh()`; the request goes Apple ↔ Apple.

Subscription management (cancellation, refunds) is performed via your Apple ID, not via PanoSlice. The Settings sheet's "How to cancel subscription" link opens Apple's subscription-management page (`https://apps.apple.com/account/subscriptions`).

## 5. Third-party SDKs

**PanoSlice embeds zero third-party SDKs**. The app uses only:

- Apple frameworks: `SwiftUI`, `PhotosUI`, `Photos`, `ImageIO`, `CoreGraphics`, `StoreKit`, `Foundation`, `Observation`.
- The PanoSlice source code itself.

There is no analytics SDK, no crash-reporting SDK, no advertising SDK, no attribution SDK, no chat / support SDK, no A/B testing SDK.

## 6. Networking

PanoSlice does not make any network requests during normal operation. The slicing pipeline runs entirely on-device. The only network activity associated with the app is:

- App Store / StoreKit requests, initiated by Apple's StoreKit framework when you interact with the paywall or tap Restore Purchases. PanoSlice does not initiate, route, or modify these requests.
- iOS's automatic background activity (notifications about app updates, Apple's anti-fraud receipt validation, etc.), which is invisible to PanoSlice and managed entirely by the OS.

## 7. Children

PanoSlice does not knowingly collect any information from anyone, including children. The app does not present any age gate because there is no collection or processing to gate.

## 8. Changes to this policy

If PanoSlice ever ships a feature that changes any claim in this document — for example, adding optional crash reporting that you must explicitly opt into — this policy will be updated in advance of the feature shipping, and the **Last updated** date at the top of this page will change.

Major changes will be communicated in the app's release notes on the App Store.

## 9. Contact

Questions about this policy can be sent to **marcos@marcosbarbero.com**.

The canonical public URL of this policy is `https://marcosbarbero.github.io/docs/pano-slicer/privacy-policy/` — the same URL registered in App Store Connect as PanoSlice's Privacy Policy URL.
