# CineScore Privacy Policy

**Effective date: 18 August 2026**

CineScore ("CineScore", "we", "us") is an Android app that generates cinematic
orchestral music with AI. This policy explains, in plain English, what data the
app handles, why, and what your rights are. It applies to the CineScore app
(package `ai.cinescore.app`) and the backend service that powers it.

**The short version:** CineScore has no user accounts, shows no ads, and includes
no analytics or tracking SDKs. The only identifier we use is a random ID created
on your device. Music you generate is stored on our servers for up to 90 days so
you can download it, then deleted. You can ask us to delete your data at any time
by emailing **rotour.dev@gmail.com**.

---

## 1. Data we collect

### 1.1 Anonymous device ID

When you first launch CineScore, the app generates a random identifier (a UUID)
and stores it on your device. This ID:

- is created by the app, not derived from your hardware, phone number, Google
  account, or advertising ID;
- is sent with every generation request so our server can enforce free-tier and
  fair-use quotas;
- is used as your subscriber ID with our billing provider (RevenueCat) so your
  Pro entitlement works without an account.

It does not identify you personally. We cannot tell who you are from it.

### 1.2 Generation requests

When you generate a piece of music, the app sends our server:

- the preset you chose (e.g. "Epic Battle"),
- the requested length in bars, and optional tempo and seed values,
- your device ID (see above).

That is the entire request. There is no free-text prompt in the current version,
and no microphone, file, or contact access is involved.

### 1.3 Generated music files

The MP3 (and, for Pro users, MIDI) files produced for you are stored on our
servers so the app can stream and download them via time-limited signed links
(links expire after 24 hours; you can re-fetch from your in-app Library while
the file is retained). Files are associated only with your device ID.

### 1.4 Purchase and subscription state

Payments are processed entirely by **Google Play**. We never see your name,
card number, or billing address. Our subscription provider, **RevenueCat**,
receives purchase tokens from Google Play and tells our app and backend whether
your device ID has an active Pro entitlement. What we hold: product identifier
(e.g. weekly or annual plan), entitlement status, and purchase timestamps —
all keyed to the anonymous device ID.

### 1.5 Support email

If you email us, we receive whatever you choose to send (typically your email
address and message). We use it only to answer you.

## 2. Data we do NOT collect

- No name, email, phone number, or postal address (no accounts exist).
- No precise or approximate location.
- No contacts, photos, files, microphone, or camera access.
- No advertising ID, and no ads of any kind.
- No analytics or crash-reporting SDKs in this version. If we ever add one,
  we will update this policy and the Play Store Data safety form first.

## 3. How we use data

| Data | Purpose | Legal basis (GDPR) |
|---|---|---|
| Device ID | Enforce free-tier quota and Pro fair-use limits; prevent abuse | Legitimate interests (fraud prevention, service integrity) |
| Generation parameters | Generate the music you asked for | Performance of a contract |
| Generated files | Let you stream/download your music | Performance of a contract |
| Purchase state | Unlock Pro features you paid for; restore purchases | Performance of a contract |
| Support emails | Answer your questions; handle deletion requests | Legitimate interests / legal obligation |

We do not use your data for advertising, profiling, or automated decisions that
produce legal effects. We do not sell data — to anyone, ever.

## 4. Who we share data with

We share data only with service providers that process it on our behalf:

- **Modal** (cloud infrastructure, USA) — runs the music-generation servers and
  stores generated files.
- **RevenueCat** (subscription management, USA) — validates purchases made
  through Google Play and manages entitlements.
- **Google Play** (Google LLC) — processes payments under its own terms and
  privacy policy.

No data is shared with advertisers, data brokers, or analytics companies.
We may disclose data if required by law, or to protect the rights, safety, or
integrity of the service.

## 5. International transfers

Our service providers process data in the United States and/or the European
Union. Where data of EU/EEA users is transferred outside the EEA, it is
protected by the providers' standard contractual clauses or an equivalent
lawful transfer mechanism. The data involved is limited to the anonymous
identifiers and content described above.

## 6. Data retention

- **Generated music files:** deleted from our servers **90 days** after
  creation. Files you have downloaded or cached stay on your device under your
  control.
- **Signed download links:** expire after 24 hours (new links can be issued
  while the file is retained).
- **Device ID and quota records:** kept while needed to operate quotas and
  entitlements; deleted on request.
- **Purchase records:** retained by RevenueCat and Google Play per their
  policies and as needed for tax/accounting law.
- **Support emails:** kept as long as needed to resolve your request.

Uninstalling the app deletes the local library and the locally stored device ID.
Server-side data then ages out per the schedule above, or immediately on request.

## 7. Security

All traffic between the app and our servers uses HTTPS (TLS). Generated files
are served only through signed, expiring URLs. API access requires an
application key. We hold no passwords or payment credentials at all.

## 8. Your rights (GDPR — EU/EEA/UK users)

You have the right to access, rectify, erase, restrict, or object to the
processing of your data, and the right to data portability. Because our only
identifier is the device ID, include it in your request (shown in
**Settings > About** in the app) so we can locate your data. To exercise any
right, email **rotour.dev@gmail.com**. We respond within 30 days. You also have
the right to lodge a complaint with your local supervisory authority.

## 9. California privacy rights (CCPA/CPRA)

We do not sell or "share" (for cross-context behavioral advertising) personal
information, and we collect only the identifiers and usage data described in
Section 1. California residents may request:

- **to know** the data we hold linked to their device ID,
- **to delete** that data,
- **non-discrimination** for exercising these rights (we never degrade service
  for privacy requests).

Submit requests to **rotour.dev@gmail.com** with your device ID. Authorized
agents may submit requests on your behalf with proof of authorization.

## 10. Children

CineScore is not directed at children under 13, and we do not knowingly collect
personal information from children. The app has no accounts, no social
features, and no ads. If you believe a child has used the service in a way that
concerns you, contact us and we will delete the associated data.

## 11. Deleting your data

Email **rotour.dev@gmail.com** from any address with the subject "Data deletion"
and your device ID. We will delete your server-side generated files, quota
records, and entitlement mapping within 30 days, and confirm by reply. Purchase
records held by Google Play are governed by Google's own policies.

## 12. Changes to this policy

We will post any changes here and update the effective date. Material changes
will be highlighted in the app's Settings screen before they take effect.

## 13. Contact

**rotour.dev@gmail.com** — privacy requests, questions, or complaints.
