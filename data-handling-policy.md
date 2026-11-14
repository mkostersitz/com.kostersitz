---
layout: default
title: Data Handling Policy
---

# Data Handling Policy

**Last updated:** November 14, 2026

This page describes, in practical terms, what data **Mike Kostersitz** handles for **Clockwork Accent**, **NullRoute**, and **Cloud Media Player**, where it goes, and how it is managed. For user-facing privacy information, see the [Privacy Policy]({{ '/privacy-policy/' | relative_url }}).

## Data inventory

### All Apps

| Data | Source | Purpose | Required or optional |
|------|--------|---------|---------------------|
| Crash logs and stack traces | Platform crash reporting (Apple / Microsoft) | Bug investigation and fixes | Optional — opt out varies by platform (see Privacy Policy) |
| Store install/usage metrics (aggregated, anonymous) | App Store Connect / Microsoft Store | Understand usage trends | Not configurable — handled by platform |
| Support email content and email address | User-submitted | Resolve support issues | Optional — only when user contacts support |

### Cloud Media Player (additional)

| Data | Source | Purpose | Required or optional |
|------|--------|---------|---------------------|
| Cloud storage OAuth token | User authorization via provider | Authenticate to cloud storage | Required for cloud features |
| File/folder list from authorized cloud path | Cloud provider API | Display media library | Required for cloud features |
| Local playback history and playlists | User actions in app | Restore playback state | Stored locally; optional (clearable in app) |

### Clockwork Accent (additional)

| Data | Source | Purpose | Required or optional |
|------|--------|---------|---------------------|
| Game save data | User gameplay | Save and restore progress | Stored locally; optionally in user's iCloud account (Apple platforms only) |

### NullRoute (additional)

| Data | Source | Purpose | Required or optional |
|------|--------|---------|---------------------|
| Game save data and settings | User gameplay | Save and restore progress | Stored locally; optionally in user's iCloud account (Apple platforms only); local only on Windows |

## Storage and access

- **Crash data:** Stored and processed by the platform (Apple on iOS/macOS, Microsoft on Windows). We access aggregate reports through the respective developer dashboards. No raw personal identifiers are available to us.
- **Support communications:** Received via email. Access is limited to Mike Kostersitz. Stored in email infrastructure subject to that provider's security practices.
- **App data (saves, settings, playlists):** Stored on the user's device. On Apple platforms, optionally synced to the user's personal iCloud account. On Windows, stored locally only. Mike Kostersitz does not have access to this data.
- **Cloud Media Player tokens:** OAuth tokens are stored in the device's secure credential store (Keychain on Apple platforms, Windows Credential Manager on Windows). They are not transmitted to our servers.

**Development and testing:** We do not use production user data in development or testing. Test builds use developer-owned accounts and locally generated test data.

## Service providers and transfers

| Provider | Data received | Purpose |
|----------|--------------|---------|
| Apple (App Store, iCloud) | Crash reports, aggregate metrics, iCloud sync | Platform services for Apple platform apps — see [Apple's privacy policy](https://www.apple.com/legal/privacy/) |
| Microsoft (Microsoft Store) | Crash reports, aggregate metrics | Platform services for Windows apps — see [Microsoft's privacy policy](https://privacy.microsoft.com) |
| User's chosen cloud provider (Cloud Media Player) | OAuth token, file/folder access | Media library access — governed by provider's own privacy policy |
| Email provider (support) | Support email content | Delivery and storage of support communications |

We do not use advertising networks, third-party analytics SDKs, or data brokers.

## Retention and deletion

| Data | Retention | Deletion method |
|------|-----------|----------------|
| Crash and diagnostic data | Per platform policies (Apple / Microsoft) | Opt out varies by platform — see Privacy Policy |
| Store metrics | Per platform policies (Apple / Microsoft) | Not configurable |
| Support emails | Up to 2 years from last contact | Email request to [support@kostersitz.com](mailto:support@kostersitz.com) |
| App data (saves, settings, playlists) | Until app is deleted or storage is cleared | Delete app, or clear via device/system app settings |
| Cloud storage OAuth token | Until revoked or app is deleted | Revoke in app Settings or in cloud provider's connected apps |

## Data requests and incidents

**Access, correction, export, or deletion requests:** Email [support@kostersitz.com](mailto:support@kostersitz.com) with the subject "Data Request." Include your name and a description of your request. We will verify your identity, respond within 30 days, and complete eligible requests within 45 days.

**Suspected data incidents:** If we become aware of unauthorized access to personal data we control (primarily support communications), we will assess the scope, contain the incident, and notify affected individuals as required by applicable law. Contact: [support@kostersitz.com](mailto:support@kostersitz.com).

## Contact

Questions about data handling: [support@kostersitz.com](mailto:support@kostersitz.com)
