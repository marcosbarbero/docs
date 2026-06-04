---
layout: default
title: VoiceScribe — Privacy Policy
permalink: /voice-scribe/privacy-policy/
---

# VoiceScribe Privacy Policy

**Effective date:** 2026-06-04
**Last updated:** 2026-06-04

This privacy policy explains how VoiceScribe ("VoiceScribe", "the app", "we", "I" — VoiceScribe is published by Marcos Barbero, a solo independent developer) handles your information. VoiceScribe is an iOS application distributed via the Apple App Store.

The short version: VoiceScribe records and transcribes audio entirely **on your device** and has no servers. By default nothing leaves your phone. The one exception is **optional iCloud Sync** — off by default — which, when you turn it on, syncs your content to *your own* private iCloud (never to us). The long version follows.

## 1. Information collected

**VoiceScribe does not collect, store, transmit, or share any personally identifiable information.**

Specifically, VoiceScribe does not collect:

- Your name, email address, phone number, postal address, or Apple ID.
- Your location, GPS coordinates, or IP address.
- Your contacts, calendar entries, or messages.
- Your device identifier (IDFA / IDFV), advertising ID, or any cross-app identifier.
- Analytics on which buttons you tap, which features you use, or how long you spend in the app.
- Crash reports (VoiceScribe embeds no third-party crash-reporting SDK; Apple's first-party crash reporting can be enabled or disabled by you in Settings → Privacy & Security → Analytics & Improvements).

Your recordings, their transcripts, and any AI insights are **your content**. They are created and stored on your device and are not transmitted to the developer under any circumstances.

## 2. Access to your data

VoiceScribe asks for two iOS permissions, both only when you start recording:

- **Microphone.** To capture the audio you record. Audio is written to the app's private storage on your device.
- **Speech Recognition.** To transcribe your recordings. Transcription runs **on-device** (`SFSpeechRecognizer` configured with `requiresOnDeviceRecognition`); the audio is not sent to Apple's servers for transcription, and the app works in airplane mode.

Both permissions are revocable at any time via iOS Settings → VoiceScribe. The summaries, highlights, and action items ("Insights") are generated on-device by Apple Intelligence (Foundation Models); entity tags (people, places, dates) use Apple's on-device natural-language framework. Neither requires a permission prompt and neither sends your content off the device.

## 3. On-device storage

VoiceScribe stores the following on your device:

- **Recordings, transcripts, and insights**, in the app's local database and sandbox (SwiftData + the app container). They remain until you delete the memo or uninstall the app. Deleting a recording removes its audio as well.
- **Your settings** (such as the iCloud Sync on/off preference and your export-format choice), in `UserDefaults` within the app's private container.

VoiceScribe writes nothing outside its own sandbox, and — with iCloud Sync off (the default) — nothing it stores ever leaves your device.

## 4. Optional iCloud Sync

iCloud Sync is **off by default.** When you turn it on (Settings → iCloud Sync), your recordings, transcripts, and insights are synced across your own devices through **your private iCloud account**, using Apple's iCloud / CloudKit private database.

- This data goes only to **your own iCloud private database**. It is **not** sent to any VoiceScribe server (there are none), is **not** accessible to the developer, and is **not** shared with anyone.
- There is **no account to create** — iCloud Sync uses the iCloud account already signed in on your device. VoiceScribe has no login, no sign-up, and no user accounts of any kind.
- You can turn it off at any time to return to local-only storage. Deleting a recording while sync is on removes it (and its audio) from your other devices too.

Apple's handling of data in your iCloud account is governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## 5. In-app subscriptions

VoiceScribe offers an optional **Scribe Pass** subscription (monthly or annual) through the Apple App Store. Subscriptions are handled entirely by Apple's StoreKit infrastructure:

- The payment transaction is between you and Apple. VoiceScribe never sees your payment method, billing address, or Apple ID email.
- Your subscription status is resolved **on-device** by Apple's StoreKit; VoiceScribe asks StoreKit "is the current user subscribed?" and StoreKit answers locally. VoiceScribe never queries a separate backend to verify your subscription.
- **Restore Purchases** calls Apple's StoreKit; the request goes Apple ↔ Apple.

Subscription management (cancellation, refunds) is performed via your Apple ID, not via VoiceScribe.

## 6. Third-party SDKs

**VoiceScribe embeds zero third-party SDKs.** The app uses only Apple's own frameworks — among them SwiftUI, AVFoundation, Speech, Foundation Models, Natural Language, SwiftData, CloudKit, and StoreKit — and the VoiceScribe source code itself.

There is no analytics SDK, no crash-reporting SDK, no advertising SDK, no attribution SDK, and no chat / support SDK.

## 7. Networking

VoiceScribe makes no network requests for its core function — recording, transcription, and insight generation all run on-device, and the app works in airplane mode. The only network activity associated with the app is:

- **App Store / StoreKit** requests, initiated by Apple's StoreKit framework when you interact with the paywall or tap Restore Purchases.
- **iCloud / CloudKit** synchronisation, **only if you have turned on iCloud Sync**, between your device and your own private iCloud database.
- iOS's automatic background activity (app-update checks, Apple's anti-fraud receipt validation, etc.), which is invisible to VoiceScribe and managed entirely by the OS.

None of these send your content to the developer.

## 8. Children

VoiceScribe does not knowingly collect any information from anyone, including children. The app presents no age gate because there is no collection or processing to gate.

## 9. Changes to this policy

If VoiceScribe ever ships a feature that changes any claim in this document, this policy will be updated in advance of the feature shipping, and the **Last updated** date at the top of this page will change. Material changes will be communicated in the app's App Store release notes.

## 10. Contact

Questions about this policy can be sent to **[marcos@marcosbarbero.com](mailto:marcos@marcosbarbero.com)**.

The canonical public URL of this policy is `https://marcosbarbero.github.io/docs/voice-scribe/privacy-policy/` — the same URL registered in App Store Connect as VoiceScribe's Privacy Policy URL.
