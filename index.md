---
layout: default
title: DocFlow Privacy Policy
---

# Privacy Policy for DocFlow

**Last updated: May 2, 2026**
**App package name: `com.docflow.pdftools`**

This Privacy Policy describes how the DocFlow mobile application ("DocFlow", "the app", "we", "our", or "us") handles your information.

The short version, in plain English: **DocFlow does not collect your data. Every document, image, signature, and setting stays on your device. We do not have a server. We have nothing to leak, sell, or hand over.**

The rest of this document explains exactly what that means.

---

## 1. Information we do NOT collect

We have intentionally built DocFlow to operate entirely on your device. Specifically, we do **not** collect, store, transmit, or have access to:

- The PDF, image, or text files you open, edit, or save
- The contents of those files (text, images, signatures, watermarks, scanned content)
- The result of any tool you run (merged PDFs, compressed PDFs, extracted text, etc.)
- Your name, email address, or contact information
- Your device's unique identifier, advertising ID, or installation ID
- Your IP address
- Your location
- Crash logs, diagnostic data, or analytics events
- Your in-app activity (which tools you use, how often, when)

There is no DocFlow server. There is no DocFlow account. There is no login.

---

## 2. Information that stays on your device

DocFlow stores certain data **locally on your device** so the app can work between sessions:

| What | Where | Why |
|---|---|---|
| Your bookmarks | Local app storage | So you can return to where you were in a PDF |
| Your favorite documents | Local app storage | So your starred items appear at the top |
| Your folders | Local app storage | So your library stays organized |
| Your saved signatures | Local app storage | So you can re-use them on future PDFs |
| Recent files list | Local app storage | So the home screen shows what you opened recently |
| Your theme preference (Light / Dark / Sepia) | Local app storage | So the app remembers your setting |
| Your subscription status | Local app storage | So premium features stay unlocked after restart |

This data never leaves your device. If you uninstall DocFlow, all of this is deleted by your operating system.

---

## 3. Permissions we request — and why

DocFlow asks for the minimum permissions required for the features you actively use:

### 📷 Camera
**Used for:** Capturing a photo when you choose to extract text via OCR (Optical Character Recognition).
**What happens with the photo:** It is processed entirely on your device using on-device machine learning (Google ML Kit). The photo and the extracted text are never uploaded anywhere by DocFlow. You can delete or share the photo at any time.

### 📁 Storage / Files / Photos
**Used for:** Reading the documents and images you open in DocFlow, and saving the results of tools (merged PDFs, signed PDFs, compressed PDFs, etc.) to your device.
**What happens with your files:** Files stay on your device. DocFlow does not copy, upload, or back up your files anywhere. When you tap "Share", you control where the file goes — DocFlow only hands it to the app you choose.

### 🌐 Internet (declared but currently unused)
The Android system requires apps to declare network permissions in advance. DocFlow declares `INTERNET` and `ACCESS_NETWORK_STATE`, but the current version makes **no network requests** of its own. Future versions may add features that require internet (e.g., subscription verification via Google Play Billing); when that happens, this policy will be updated and the change will be clearly disclosed.

### 🔓 Manage all files (`MANAGE_EXTERNAL_STORAGE`)
**Used for:** Letting you open and save PDFs from any folder on your device (Downloads, Documents, app folders, etc.) without re-prompting for each location.
**What happens:** This permission only enables file access for actions you explicitly initiate (opening a file, saving a result). DocFlow does not scan your storage in the background, does not enumerate your files, and does not share file lists with anyone.

---

## 4. On-device machine learning (OCR)

DocFlow uses **Google ML Kit's on-device text recognition** to extract text from images and PDFs. According to Google's ML Kit documentation, the on-device version of text recognition runs entirely on your device — input images and recognized text are not sent to Google's servers by ML Kit.

DocFlow only invokes the on-device API. We do not use the cloud version of ML Kit.

---

## 5. Sharing and exporting

When you tap "Share" on a document inside DocFlow, you trigger your operating system's share sheet, which lets you send the file to another app you choose (email, messaging, cloud drives, etc.). DocFlow's role ends the moment you pick a destination.

What happens to your file after that point is governed by the privacy policy of the app you sent it to (Gmail, WhatsApp, Google Drive, Dropbox, etc.) — not by DocFlow.

---

## 6. In-app purchases (subscription)

DocFlow offers an optional **Premium subscription** that unlocks advanced tools (unlimited OCR, watermarks, redaction, password protection, and more).

- Subscriptions are processed by **Google Play Billing**. DocFlow never receives or stores your payment card, billing address, or other financial details. That information is handled by Google.
- DocFlow only stores a record of whether your subscription is active or expired, locally on your device.
- For Google's handling of your purchase data, see the [Google Play Privacy Policy](https://play.google.com/intl/en/about/play-terms/).

---

## 7. Children's privacy

DocFlow is not directed at children under the age of 13. We do not knowingly collect data from anyone — including children — because we do not collect data at all (see Section 1). The app does not contain features designed to attract children, and contains no advertising.

---

## 8. Third-party services

DocFlow currently uses the following third-party libraries that run on your device. None of them transmit your file content, identifiers, or behavior to a remote server in this application:

- **Google ML Kit (text recognition)** — on-device only
- **Syncfusion Flutter PDF, pdf, pdfx, printing** — local PDF processing
- **Hive, sqflite** — local data storage
- **Other Flutter packages** — UI, file picking, sharing, animations

If a future version of DocFlow integrates a service that does collect data (for example, an analytics SDK or cloud sync), this policy will be updated to disclose the service, the data collected, and how to opt out.

---

## 9. Data deletion

Because DocFlow does not collect, store, or transmit any of your data to our servers, there is nothing for us to delete on your behalf.

To delete the data DocFlow stores locally on your device, simply uninstall the app. Your operating system will remove all app data — including bookmarks, favorites, signatures, recent files, and any documents DocFlow created.

---

## 10. Your rights under GDPR, CCPA, and similar laws

Privacy laws in your region may give you specific rights — including the right to access, correct, delete, or port your personal data, and the right to object to its processing.

These rights apply to the data a company holds about you. **DocFlow does not hold any data about you**, so there is nothing to access, export, or delete on our side. If you live in a jurisdiction that requires us to confirm this in writing, contact us at the email below and we will respond.

---

## 11. Changes to this policy

If we change this policy in a way that affects how the app handles your data — for example, adding a feature that requires network access or integrating an analytics service — we will:

1. Update the "Last updated" date at the top of this page
2. Disclose the change in the app's release notes
3. For material changes (new data collection), require you to acknowledge the change in-app before continuing to use affected features

---

## 12. Contact

Questions, concerns, or privacy requests:

📧 **er.varunvision@gmail.com**

We aim to respond within 7 days.

---

*DocFlow is built with respect for your time, your privacy, and your files. If anything in this policy is unclear, please tell us — we'd rather rewrite it than have you wonder.*
