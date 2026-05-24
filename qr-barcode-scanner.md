# QR & Barcode Scanner — Privacy Policy

**App name:** QR & Barcode Scanner (Android package `com.qrflow.qrflow`)
**Developer:** CodeOrbit Labs
**Contact:** er.varunvision@gmail.com
**Last updated:** May 24, 2026

This Privacy Policy describes how the **QR & Barcode Scanner** mobile application (referred to below as "the app", "we", "our", or "us"), published on Google Play by **CodeOrbit Labs**, handles your information.

The short version, in plain English: **the app does not collect your data. Every QR code, barcode, scan, theme, and setting stays on your device. We do not have a server. We have nothing to leak, sell, or hand over.**

The rest of this document explains exactly what that means.

---

## 1. Information we do NOT collect

We have intentionally built the app to operate entirely on your device. Specifically, we do **not** collect, store, transmit, or have access to:

- The QR codes or barcodes you scan, create, or save
- The contents of those codes (URLs, contacts, WiFi credentials, locations, payment info, etc.)
- Your name, email address, or contact information
- Your device's unique identifier, advertising ID, or installation ID
- Your IP address
- Your location (except when you explicitly create a location-based QR code — see Section 3)
- Crash logs, diagnostic data, or analytics events
- Your in-app activity (which features you use, how often, when)

There is no CodeOrbit Labs server collecting this data. There is no account. There is no login.

---

## 2. Information that stays on your device

The app stores certain data **locally on your device** so it can work between sessions:

| What | Where | Why |
|---|---|---|
| Your scan history | Local database (SQLite) | So you can revisit previously scanned codes |
| Your saved QR codes & barcodes | Local database (SQLite) | So your created codes are available in your library |
| Your scanned documents | Local app storage | So document scans persist between sessions |
| Your custom QR themes | Local database (SQLite) | So you can reuse your favorite QR code designs |
| Your favorites | Local app storage | So starred items appear at the top |
| Your app settings (theme, language, haptics, sounds) | SharedPreferences | So the app remembers your preferences |
| Your subscription status | SharedPreferences | So premium features stay unlocked after restart |
| Your free-tier code count | SharedPreferences | So the free usage limit is tracked locally |
| Home widget configurations | Local app storage | So your home screen widgets display the correct codes |
| Food product cache | Local storage (Hive) | So barcode lookups are faster on repeat scans (expires after 7 days) |
| Exchange rate cache | Local storage | So currency conversions work offline (expires after 24 hours) |

This data never leaves your device. If you uninstall the app, all of this is deleted by your operating system.

---

## 3. Permissions we request — and why

The app asks for the minimum permissions required for the features you actively use:

### Camera
**Used for:** Scanning QR codes and barcodes using your device camera, and document scanning.
**What happens with the camera feed:** It is processed entirely on your device in real-time. The camera feed is never recorded, stored, or transmitted. Once a code is detected, only the decoded text content is saved to your scan history — not the camera image.

### Storage / Files / Photos
**Used for:** Saving generated QR code images (PNG, SVG, PDF) to your gallery, picking images for QR code center logos, and storing scanned documents.
**What happens with your files:** Files stay on your device. The app does not copy, upload, or back up your files anywhere. When you tap "Share", you control where the file goes — the app only hands it to the destination app you choose.

### Location
**Used for:** Creating location-based QR codes only. The app requests location access only when you explicitly choose to generate a QR code containing your current coordinates.
**What happens with your location:** Your coordinates are used solely to populate the QR code content. They are stored locally as part of the saved QR code data. Your location is never transmitted to any server.

### Internet
**Used for:** Two optional features only — food product lookup (OpenFoodFacts API) and currency exchange rates (see Section 5). Core scanning and QR code generation work entirely offline with no internet required.

### Vibration
**Used for:** Haptic feedback when scanning codes. Can be disabled in app settings.

---

## 4. Sensitive data you may store in QR codes

The app allows you to create QR codes containing sensitive information such as:

- **WiFi passwords** — stored locally as QR code content
- **Contact details** — names, phone numbers, email addresses, physical addresses
- **Payment information** — cryptocurrency addresses, PayPal, UPI, Venmo details
- **Location coordinates** — GPS latitude and longitude

**All of this data is stored exclusively on your device** in the app's local database. It is never transmitted to any server. When you share a QR code image, you are choosing to share that data — the app simply generates the image for you.

---

## 5. Third-party services

The app makes minimal, optional network requests to the following public APIs. No personal information, device identifiers, or tracking data is sent with these requests:

### OpenFoodFacts API
**When:** You scan a food product barcode and the app looks up product information.
**What is sent:** Only the barcode number.
**What is received:** Product name, nutrition facts, and ingredients from the [OpenFoodFacts](https://openfoodfacts.org) open-source community database.
**Caching:** Results are cached locally for 7 days to minimize API calls.

### Exchange Rate API
**When:** You use currency conversion features for payment QR codes.
**What is sent:** Only the currency code (e.g., "USD").
**What is received:** Current exchange rates.
**Caching:** Results are cached locally for 24 hours.

---

## 6. Sharing and exporting

When you share a QR code, barcode, or export a PDF from the app, you trigger your operating system's share sheet, which lets you send the file to another app you choose (email, messaging, social media, etc.). The app's role ends the moment you pick a destination.

What happens to your file after that point is governed by the privacy policy of the app you sent it to — not by us.

QR themes can be shared with other users via QR code or JSON export. Shared themes contain only design data (colors, shapes, styles) — no personal information.

---

## 7. Home screen widgets

The app offers home screen widgets that display your saved QR codes. Widget data (code content and cached images) is stored locally on your device using the standard platform widget storage. No widget data is transmitted externally.

---

## 8. In-app purchases (subscription)

The app offers an optional **Premium subscription** that unlocks advanced features.

- Subscriptions are processed by **Google Play Billing**. We never receive or store your payment card, billing address, or other financial details. That information is handled by Google.
- The app only stores a record of whether your subscription is active or expired, locally on your device.
- For Google's handling of your purchase data, see the [Google Play Privacy Policy](https://play.google.com/intl/en/about/play-terms/).

---

## 9. Children's privacy

The app is not directed at children under the age of 13. We do not knowingly collect data from anyone — including children — because we do not collect data at all (see Section 1). The app does not contain features designed to attract children, and contains no advertising.

---

## 10. Data deletion

Because the app does not collect, store, or transmit any of your data to our servers, there is nothing for us to delete on your behalf.

To delete the data the app stores locally on your device:
- **Individual items:** Delete specific scan history entries, saved codes, or themes from within the app at any time.
- **All data:** Uninstall the app. Your operating system will remove all app data — including scan history, saved codes, themes, settings, and cached data.

---

## 11. Your rights under GDPR, CCPA, and similar laws

Privacy laws in your region may give you specific rights — including the right to access, correct, delete, or port your personal data, and the right to object to its processing.

These rights apply to the data a company holds about you. **CodeOrbit Labs does not hold any data about you through this app**, so there is nothing to access, export, or delete on our side. If you live in a jurisdiction that requires us to confirm this in writing, contact us at the email below and we will respond.

---

## 12. Changes to this policy

If we change this policy in a way that affects how the app handles your data — for example, adding a feature that requires network access or integrating an analytics service — we will:

1. Update the "Last updated" date at the top of this page
2. Disclose the change in the app's release notes
3. For material changes (new data collection), require you to acknowledge the change in-app before continuing to use affected features

---

## 13. Contact

Questions, concerns, or privacy requests:

er.varunvision@gmail.com
**CodeOrbit Labs**

We aim to respond within 7 days.

---

*QR & Barcode Scanner is built by CodeOrbit Labs with respect for your privacy. If anything in this policy is unclear, please tell us — we'd rather rewrite it than have you wonder.*
