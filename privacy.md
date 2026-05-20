---
layout: default
title: Privacy Policy
permalink: /privacy
---

# CampsiteLog Privacy Policy

**Effective date:** May 20, 2026

## Who we are

CampsiteLog is an iOS app for keeping a personal log of the campsites you have stayed at. It is built and maintained by Ryan Smith as a one-person project. Questions about this policy can be sent to **ryansmith1856@proton.me**. This policy covers the CampsiteLog iOS app distributed through Apple's App Store; it does not cover any other product.

## What we store on your device

Everything you enter into CampsiteLog is saved locally on your iPhone. That includes:

- Your campsite reviews — campground name, site number, ratings, notes, dates, and any of the optional fields (privacy, vibe, surface, maneuverability, cell signal).
- Photos you choose to attach to a review, stored under the app's Application Support directory.
- Your equipment profiles (e.g. tent, RV length).
- Your free-text cell carrier name, if you set one in Settings.
- Per-site coordinates that you tap "Use my location" to capture in the Record screen.

By default, none of this is uploaded anywhere. Reviews stay on your phone unless you explicitly export them or opt in to Cloud Backup.

## What we collect when you opt in to Cloud Backup

Cloud Backup is an optional, paid feature. When you turn it on, CampsiteLog uploads copies of your reviews and photos to our backend (hosted on Convex) over an encrypted connection (TLS). Data is stored encrypted at rest by our hosting provider. It is
not end-to-end encrypted — as the developer, I have technical access to it for support and operations purposes, but I do not analyze it, share it with advertisers, or sell it.

## What we do not collect

CampsiteLog does not include advertising SDKs, advertising identifiers
(IDFA), crash-reporting services, or third-party trackers. We do collect
a small amount of product-interaction data to understand how new users
move through the first-launch onboarding flow — see "Onboarding
analytics" below. We do not collect:

- Your contacts, calendars, or browsing history.
- Advertising identifiers (IDFA).
- Background location.
- Anything from other apps on your device.

## Onboarding analytics

To improve the first-launch experience, CampsiteLog records anonymous
events for each onboarding step (e.g. "viewed welcome screen", "skipped
profile setup", "tapped subscribe"). Each install is identified by a
random UUID generated on your device — it is not linked to your Apple
ID, your name, your email, or any other identifying information. The
events are sent to our backend (Convex). They contain no review content,
no photos, and no location data.

## Location

CampsiteLog asks for "When in Use" location access. Your location is read only at the moment you tap the site-pin button in the Record screen, and only to capture a single coordinate for that one review. The coordinate is stored locally on your phone. It is uploaded only if Cloud Backup is enabled.

## Photos and camera

CampsiteLog asks for permission to read your photo library and to use the camera so that you can attach photos to a review. Photos you select or take are saved as files in the app's Application Support directory. Like the rest of your data, they stay on your phone unless Cloud Backup is enabled.

## Subscriptions and payments

Subscriptions and tips are processed entirely by Apple through the App Store. We never see your credit-card number, your Apple ID password, or your billing address. We receive only the anonymous transaction metadata Apple provides (product identifier, expiration date, renewal status) so that the app knows whether your subscription is active.

## Children

CampsiteLog is not directed at children under 13 and we do not knowingly collect any information from them.

## Your choices and rights

- **Delete a single review.** Open it in the History tab and tap Delete.
- **Wipe all local data.** Delete the CampsiteLog app from your iPhone. iOS will remove its sandbox, including reviews and photos.
- **Cancel a subscription.** iOS Settings → your name → Subscriptions → CampsiteLog.
- **Export your data.** Settings → Your data → Export reviews (JSON) or Full backup (.campsitelog).

If you want a copy of any data we hold for you in Cloud Backup, or you want it deleted from our servers, email **ryansmith1856@proton.me** and we'll handle it within a reasonable time.

## Changes to this policy

If this policy changes in any meaningful way, we'll update the effective date above and post a note in the app's About section. Past versions are visible in this repo's commit history.

## Contact

**Ryan Smith** — ryansmith1856@proton.me
