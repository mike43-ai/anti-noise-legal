---
title: Privacy Policy — Anti Noise
permalink: /privacy/
---

# Privacy Policy

**Effective date:** May 19, 2026
**Last updated:** May 19, 2026

Anti Noise ("we", "us", "our") operates the Anti Noise iOS application (the "App"). This Privacy Policy explains what information we collect, how we use it, and the choices you have. By using the App you agree to this policy.

## 1. Information We Collect

### 1.1 Account information
When you sign up with email + password or Sign in with Apple, we collect:
- Email address
- Display name (optional, you may provide it)
- Account identifier issued by our authentication provider

### 1.2 Content you create
The App captures content you choose to save:
- URLs, text notes, and images you submit through the Capture flow or iOS Share Sheet
- AI-generated summaries and flashcards derived from your captures
- Focus session timestamps and durations
- Tags, categories, and personal notes attached to captures

This content is stored locally on your device (SwiftData) and mirrored to our cloud database (Cloud Firestore) when you are signed in, so you can access it across your devices.

### 1.3 Subscription information
When you purchase a subscription, the App receives a receipt from Apple confirming entitlement. We do not receive your payment method, billing address, or full Apple ID. Apple charges you directly; we only see whether your subscription is active.

### 1.4 Diagnostic information
We collect anonymous app usage events (screens viewed, features used, capture counts, subscription events) and crash reports to improve the App. Diagnostic data is associated with a random installation identifier, not with your real identity.

### 1.5 Information you do not provide
The App does not ask for your phone number, location, contacts, calendars, or health data.

## 2. How We Use Your Information

We use the information we collect to:
- Provide the core capture, summarize, and learning features
- Sync your content across your devices
- Generate AI summaries and flashcards from your captures
- Enforce free-tier quotas (3 captures per day, 5 AI summaries per month) and unlock unlimited usage for Pro subscribers
- Send local notifications (review reminders for spaced-repetition flashcards) — these notifications are scheduled on your device and do not require us to send data through external servers
- Diagnose crashes and improve performance
- Communicate with you about service changes or support requests when you contact us

We do not use your content to train AI models. We do not sell your information to advertisers or data brokers.

## 3. AI Processing (OpenAI)

The App uses OpenAI's GPT-4o to generate Feynman-style summaries and flashcards. When you request a summary, the text content of the capture is sent to OpenAI's API. OpenAI's data handling is governed by OpenAI's own privacy policy: https://openai.com/policies/privacy-policy.

In the current version, AI calls are made using an API key that you provide and that is stored only in your device Keychain. We do not retain or relay your captures through our servers in this configuration. A future update will route AI calls through our backend; this policy will be updated when that change ships.

## 4. Third-Party Services

We rely on the following third-party services to operate the App. Each receives only the information necessary to perform its function:

| Service | Purpose | Data received |
|---|---|---|
| Apple — Sign in with Apple, App Store | Authentication, in-app purchases | Email (relay or real), purchase receipt |
| Google Firebase — Authentication | Account sign-in | Email, display name |
| Google Cloud Firestore | Cloud database | Your captures, summaries, flashcards, account profile |
| Google Firebase Analytics | Anonymous usage analytics | Installation ID, event names, screen names |
| Google Firebase Crashlytics | Crash reporting | Crash stack traces, device model, OS version |
| OpenAI | AI summary + flashcard generation | Capture text content (only when you trigger a summary or flashcard) |
| RevenueCat | Subscription management | App User ID (random or your Firebase UID), purchase receipts |

Each provider stores data on their own infrastructure under their respective privacy policies. We do not control how these providers process data within their platforms.

## 5. Data Retention

- **Account and content data** are retained while your account is active.
- **Account deletion**: you can request account deletion in the App (Profile → Delete Account). After confirmation we apply a 7-day soft-delete window during which the action can be reversed by contacting support. After 7 days your account, captures, summaries, and flashcards are permanently removed from our cloud database. Local data on your device is removed immediately when you delete the account or uninstall the App.
- **Diagnostic data** is retained for up to 12 months and then aggregated or deleted, in line with Firebase Analytics defaults.
- **Receipts and subscription history** are retained for the lifetime of your subscription plus any period required by tax or accounting law.

## 6. Your Rights

Depending on your jurisdiction (GDPR, CCPA, Vietnam PDPL, etc.), you may have the right to:
- Access the personal information we hold about you
- Correct inaccurate information
- Request deletion of your data
- Export your data (the App supports JSON export under Profile → Export Data)
- Withdraw consent for processing
- Lodge a complaint with your data protection authority

To exercise these rights, contact us at the email below. We respond within 30 days.

## 7. Children

Anti Noise is not directed at children under 13 (or the equivalent minimum age in your country). We do not knowingly collect data from children under that age. If you believe a child has provided data to us, contact us and we will delete it.

## 8. Security

We use industry-standard measures to protect your information:
- TLS for all data in transit
- Encrypted storage on Apple and Google managed infrastructure
- API keys stored in the iOS Keychain on your device
- Access to production data restricted to the operator of Anti Noise

No system is perfectly secure. If you believe your account has been compromised, contact us immediately.

## 9. International Transfers

We are based in Vietnam. Your information may be processed in the United States or other countries where our service providers operate. By using the App, you consent to such transfers. Where required by law (e.g. GDPR), we rely on standard contractual clauses or equivalent safeguards offered by our providers.

## 10. Changes to This Policy

We may update this policy from time to time. We will post the new version at this URL and update the "Last updated" date. Material changes will be announced inside the App. Continued use of the App after the change takes effect constitutes acceptance of the updated policy.

## 11. Contact

For privacy questions, data requests, or any other inquiries:

**Email:** support.gravita@gmail.com

We aim to respond within 5 business days.
