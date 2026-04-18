---
layout: page
title: Privacy Policy
include_in_header: false
---

**Last updated**
April 2026

# Privacy Policy

At **YouClip**, your privacy matters. This policy explains what data the app processes, where, and why.

<br>

## 1.0 Summary

- Summaries are generated **on your device by default** — nothing leaves your iPhone.
- The optional Pro cloud summarization sends the video transcript to our EU backend, which relays it to a third-party AI provider. We do not store it.
- We do not sell your data. We do not have user accounts. No third-party tracking beyond the analytics described below.

<br>

## 2.0 Who We Are

**YouClip** is published by **SixtyEdge**. For any privacy-related request, contact us at **sixtyedge@gmail.com**.

<br>

## 3.0 Data Processed On Your Device

All of the following stays on your device and is not transmitted to SixtyEdge:

- **Video history, transcripts, comments, and generated summaries**, stored locally via SwiftData
- **App preferences** (selected summarization mode, language), stored in `UserDefaults`
- **Usage counters** (free quota tracking), stored in the iOS Keychain

Uninstalling the app removes all of this data from your device.

<br>

## 4.0 Requests Sent to YouTube

When you paste a YouTube URL or share a video to YouClip, the app fetches the transcript and public comments directly from YouTube's public APIs, **from your device**. These requests include the video ID and a randomly generated visitor identifier. They do not include any personal information about you.

YouTube (operated by Google) processes these requests under its own privacy policy.

<br>

## 5.0 Cloud Summarization (Pro Only)

If you are a YouClip Pro subscriber and you select the cloud summarization mode, the video transcript is sent to our backend at `europe-west1-youclip-app-2026.cloudfunctions.net` (Google Cloud Functions, EU region, Belgium).

Our backend:
- Acts as a stateless proxy
- Forwards the transcript to a third-party AI provider
- Returns the generated summary to your device
- **Does not persist the transcript or the summary**

The third-party AI provider processes the transcript under its own privacy policy. We do not share any personal identifier with them — only the transcript text and the summarization parameters (mode, language).

<br>

## 6.0 Analytics

YouClip uses **Firebase Analytics** (Google) to understand anonymous, aggregated app usage. This helps us improve the product.

The following may be collected:
- App usage events (screens viewed, features used)
- Device information (model, iOS version, language, region)
- Session duration
- A randomly generated, anonymous app instance identifier

Firebase Analytics does **not** process the content of your videos, transcripts, or summaries. Data is processed by Google under its own privacy policy. You can opt out of personalized data use via your device settings (Settings → Privacy & Security → Tracking and Apple Advertising).

<br>

## 7.0 In-App Purchases

YouClip Pro is sold through Apple's in-app purchase system. Payment, billing, and receipts are handled entirely by Apple. We do not receive your payment details. We use StoreKit to verify your subscription status locally on your device.

<br>

## 8.0 Third Parties

- **Apple** — App Store, StoreKit, Apple Intelligence (on-device)
- **Google** — YouTube public APIs, Cloud Functions hosting, Firebase Analytics, third-party AI provider (for Pro cloud summaries)

Your use of these services is subject to their own privacy policies.

<br>

## 9.0 Data Retention

- On-device data: kept until you delete it or uninstall the app.
- Cloud summarization requests: not retained by our backend.
- Firebase Analytics: retained according to Firebase's default retention window.

<br>

## 10.0 Your Rights (GDPR)

Because YouClip is published from the European Union, you have the right to:

- Access the data we hold about you
- Request correction or deletion
- Object to processing
- File a complaint with a data protection authority (CNIL in France)

To exercise these rights, email **sixtyedge@gmail.com**. Note that most of your data is already stored only on your device and is not accessible to us.

<br>

## 11.0 Children

YouClip is not directed at children under 13. We do not knowingly collect data from children.

<br>

## 12.0 Changes to This Policy

We may update this policy. The "Last updated" date at the top will reflect any change.

<br>

## 13.0 Contact

**sixtyedge@gmail.com**

<br>

---
