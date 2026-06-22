# Privacy Policy

**Last updated:** June 22, 2026

## Overview

ShadeGuard is a Chrome browser extension that detects manipulative dark patterns on websites. This privacy policy explains what data ShadeGuard accesses, how it is used, and our commitments to your privacy.

## What Data ShadeGuard Accesses

While scanning web pages for dark patterns, ShadeGuard accesses the following:

- **Visible page text:** The extension reads text content displayed on web pages to scan for dark pattern language (for example: "Only 3 left!", "ends in 02:14:33", "No thanks, I don't want to save money").
- **DOM structure:** The extension examines HTML elements and CSS class names to detect dark pattern markup (for example: countdown timer elements, scarcity badges, coupon popups).
- **Page URL and title:** The extension reads the current page URL and title to display detection results and store them locally per domain.

## What ShadeGuard Does NOT Collect

- ShadeGuard does NOT collect personally identifiable information (names, email addresses, physical addresses, phone numbers, etc.).
- ShadeGuard does NOT collect or transmit payment information, credit card numbers, or financial data.
- ShadeGuard does NOT collect health information, location data, or biometric data.
- ShadeGuard does NOT collect passwords, authentication credentials, or security questions.
- ShadeGuard does NOT read personal communications (emails, text messages, chat messages).
- ShadeGuard does NOT log keystrokes, mouse movement, scroll position, or clicks.
- ShadeGuard does NOT use analytics, tracking pixels, telemetry, or any form of remote monitoring.
- ShadeGuard does NOT sell, share, or transfer any data to third parties.
- ShadeGuard does NOT use or transfer data for purposes unrelated to dark pattern detection.
- ShadeGuard does NOT use or transfer data to determine creditworthiness or for lending purposes.

## How Data Is Used

All data accessed by ShadeGuard is used exclusively for the following purposes:

- **Dark pattern detection:** Scanning page text and DOM elements to identify manipulative design tactics across 14 categories (fake countdowns, false scarcity, hidden fees, subscription traps, confirmshaming, and more).
- **Local display:** Showing detection results in the extension popup and as a floating banner on the page.
- **Local storage:** Saving detection results per domain in Chrome's local storage so you can review them later in the History tab.
- **Trust Calibration (optional):** If you choose to give feedback on detections with 👍/👎 buttons, your responses (which detection you agreed or disagreed with) are stored locally to show your personal accuracy stats. This feedback is scoped per domain and never transmitted.
- **Cross-domain pattern tracking:** A count of how many sites have used each dark pattern type is stored locally to show you pattern prevalence across the web.

## Data Storage

- Detection results are stored in `chrome.storage.local` on your device.
- User settings (which detection categories are enabled or disabled, accessibility preferences) are stored locally.
- Optional feedback on detections (👍/👎) is stored locally, scoped per domain.
- Cross-domain pattern statistics are stored locally.
- Results for the most recent 50 visited domains are kept. Older results are automatically deleted.
- You can clear all stored data at any time by clicking the "Clear" button in the extension's Settings tab.

## Data Retention

All data is stored locally on your device and is automatically deleted when you uninstall the extension. ShadeGuard does not maintain any external servers, databases, or cloud storage.

## Third-Party Services

ShadeGuard does not connect to, communicate with, or send data to any third-party services, APIs, servers, or external websites for the purpose of dark pattern detection. The extension is entirely self-contained for all scanning and detection functionality.

### Remote Announcements (Non-Critical)

ShadeGuard optionally fetches a small JSON file from GitHub Pages to display announcements in the extension popup. This is a one-way, read-only request:

- **URL:** `https://m1lloo.github.io/ShadeGuard-/announcements.json`
- **What is sent:** Nothing. No data, identifiers, or personal information is transmitted.
- **What is received:** A JSON object containing a `message` (string) and `show` (boolean) field.
- **Purpose:** To display optional announcements (e.g., new features, bug fixes) to users.
- **Frequency:** At most once every 5 minutes, cached locally.
- **Failure behavior:** If the request fails (network error, GitHub Pages unavailable), the extension continues to work normally. Announcements are non-critical.

No personal data is ever sent to GitHub or any other external service.

## Permissions

ShadeGuard requests the following Chrome permissions:

- **activeTab:** Used to access the current tab so the content script can scan page content for dark patterns.
- **storage:** Used to save detection results, user settings, optional feedback, and pattern statistics locally on your device.
- **scripting:** Used to inject detection scripts into web pages.

These permissions are used solely for the purpose of detecting dark patterns and displaying results to the user.

## Children's Privacy

ShadeGuard is not directed at children under 13 and does not knowingly collect personal information from children.

## Changes to This Policy

We may update this privacy policy from time to time. Any changes will be reflected in the extension's update notes on the Chrome Web Store.

## Contact

If you have questions about this privacy policy, please open an issue on our GitHub repository or contact us at the email address listed on our Chrome Web Store listing.

---

*ShadeGuard Privacy Policy | Chrome Web Store Extension*
