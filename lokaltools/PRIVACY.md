# Privacy Policy — LokalTools

**Effective Date:** 2026-10-16
**Developer:** MLOGICTECH
**Contact:** support@mlogictech.com
**App Website:** https://mlt-solutions.github.io/app-legal-docs/lokaltools

---

## Summary

LokalTools is an **offline-first** file workspace with PDF, image, video and file tools for iPhone and iPad. Every tool runs **entirely on your device**. Your files are never uploaded to any server, the app has no account or sign-in, and it contains no analytics, crash reporting, advertising or tracking.

<!-- [INCLUDE ONLY IF SHIPPED — ADS] If an ad-supported free tier ships, rewrite this
     summary and section 1: "no advertising or tracking" and "device identifiers / IP
     addresses" stop being true. Also update PrivacyInfo.xcprivacy, the App Store App
     Privacy label and add NSUserTrackingUsageDescription before release. -->

---

## 1. Data We Do NOT Collect

We do not collect, store, or transmit:

- Personal information of any kind (name, email, location, etc.)
- The contents, names, or paths of any files you open, scan, or process
- Photos, scans, faces, or text recognised in your files
- Passwords you type to open protected files
- Usage analytics, crash reports, or telemetry
- Device identifiers, IP addresses, or network information

LokalTools does not track you across apps or websites, and we do not sell or share personal data.

---

## 2. Data Stored on Your Device

The app stores the following data for its own operation. None of it is sent to us.

| Data | Storage Location | Purpose |
|------|-----------------|---------|
| Files you save, import, scan, or create with a tool | App `Documents/` folder ("On This Device", also visible in the Files app) or the app's iCloud Drive container | Your files |
| Working copies used while a tool runs | App container (Application Support) | Processing inputs and step outputs; lets an interrupted job be reported or recovered |
| Preview cache | App container | Faster previews — clear it in **Settings → Storage** |
| Recent activity and favourites (file name, type of action, time) | On-device database (SwiftData) | The **Recent** tab |
| Connected Folders | System folder bookmarks in UserDefaults (`NSUserDefaults`) | Reopening folders you chose |
| Quick Access pins | UserDefaults in the App Group container | Pinned folders |
| App preferences (appearance, language, sort, layout) | UserDefaults | App behaviour settings |

**Passwords:** if you type a password to open a protected PDF or archive, it is used once, on your device, for that file only. It is never saved and never transmitted.

**Device backups:** data in the app container may be included in your iCloud Backup or computer backup, depending on your device settings. Those backups are handled by Apple or your computer, not by us.

### iCloud Drive

If you are signed in to iCloud with iCloud Drive enabled, LokalTools can keep files in its own iCloud Drive container (`iCloud.com.mlogictech.lokaltools`). This data is:

- Stored in **your own iCloud account** — we have no access to it
- Governed by [Apple's iCloud Terms of Service](https://www.apple.com/legal/internet-services/icloud/)
- Encrypted by Apple both in transit and at rest

### Connected Folders

You can connect any folder available in the iOS Files picker — a folder on your device, an external drive, a network server (SMB), or a third-party storage provider's app. LokalTools reads and writes only the folders you pick, through Apple's file system. Any network transfer is performed by iOS or by that provider's app under its own terms and privacy policy. LokalTools does not receive or store your server or provider credentials.

<!-- [INCLUDE ONLY IF SHIPPED — SUBSCRIPTION]
### Apple StoreKit

The app uses **Apple StoreKit 2** to validate subscription purchases and restore entitlements across your Apple devices.

- Payment is handled entirely by Apple — we never receive your name, Apple ID, payment card, or billing address
- The subscription status is checked on your device; Apple may share transaction information with us (transaction ID, product, purchase and renewal dates, storefront country, refund status), used only to provide the subscription, answer support requests, and meet accounting obligations
- Purchase entitlement is managed by Apple and subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/)
-->

---

## 3. File Processing

All tools — PDF merge, split, rotate, compress, watermark and OCR; image resize, convert, compress, crop and metadata removal; images to PDF; background removal; passport photo and ID card layouts; QR codes; face blurring; video compression, conversion, audio extraction, GIF and merging; batch rename; and duplicate finding — run on your device. LokalTools:

- Reads only the files you select or share to it
- Uses Apple frameworks on-device (Vision and VisionKit for text recognition, face and rectangle detection, background removal, and document scanning; PDFKit, ImageIO and AVFoundation for documents and media)
- Writes results as new files in the location you choose
- Does **not** upload, transmit, or cache file content to any external server

---

## 4. Device Permissions

LokalTools asks for a permission only when you use the feature that needs it. You can change your choice at any time in the iOS Settings app.

| Permission | Used For | What We Receive |
|------------|----------|-----------------|
| Camera | Scanning documents and ID cards with Apple's document scanner | Nothing — scans are saved on your device as files |
| Photos (add only) | Saving a processed image when you tap **Save to Photos** | Nothing — the app can add photos but cannot read your library |

To import photos, LokalTools uses Apple's system photo picker, which gives the app only the items you select.

---

## 5. Share Extension

The iOS Share Extension lets you send files to LokalTools from other apps (Photos, Mail, Files, etc.).

- Shared files are copied into the App Group container (`group.com.mlogictech.lokaltools`), which only LokalTools and its Share Extension can read
- The main app shows them in the Import Inbox on next launch; they are removed from the inbox once you save or discard them
- No shared data is transmitted outside the device

---

## 6. Network Access

LokalTools contains no networking code of its own and makes no connections to our servers. The only network activity is:

- **iCloud Drive (if enabled):** files in the LokalTools iCloud folder sync via your personal iCloud account, performed by Apple. We have no access to this data.
- **Connected Folders on network servers or storage providers:** transfers are performed by iOS or the provider's app, not by LokalTools.
- **Contact Support:** tapping **Settings → Contact Support** opens your email app; nothing is sent until you send the email yourself.

<!-- [INCLUDE ONLY IF SHIPPED — SUBSCRIPTION] - **Apple StoreKit:** used to validate your subscription or restore purchases. Handled entirely by Apple. -->
<!-- [INCLUDE ONLY IF SHIPPED — ADS] - **Advertising:** the ad SDK (see section 7) connects to the ad provider's servers to request, display and measure ads. -->

---

<!-- [INCLUDE ONLY IF SHIPPED — ADS]
## 7. Advertising

The free version of LokalTools shows ads provided by [AD NETWORK, e.g. Google AdMob (Google Mobile Ads SDK), Google LLC]. Subscribers [do not see ads / EDIT].

**The ad provider, not LokalTools, collects data to show and measure ads.** The ad SDK may collect:

- Your device's advertising identifier (IDFA) — **only if you allow tracking** when iOS asks
- Your IP address, from which an approximate (not precise) location may be inferred
- Device and app information (device model, iOS version, language, app version)
- Ad interactions, diagnostics, and performance data used to deliver and measure ads and prevent fraud

The ad SDK does **not** receive your files, file names, scans, photos, or tool results.

**Your choices:**

- **App Tracking Transparency:** if you tap **Ask App Not to Track**, the IDFA is not available and ads are not personalised by tracking across other companies' apps and websites. Change this any time in **Settings → Privacy & Security → Tracking**.
- **EEA, UK and Switzerland:** before ads are shown, the app asks for your consent through [Google's User Messaging Platform / CMP NAME]. Change your choice any time from [LOCATION IN APP].
- **US state privacy laws:** where applicable, opt out of the "sale" or "sharing" of personal information for targeted advertising from [LOCATION IN APP].

Learn how the ad provider uses data: [e.g. https://policies.google.com/technologies/partner-sites]

---
-->

## 7. Support Email

If you contact us, we receive your email address and whatever you include in your message. We use it only to reply and help you, and keep it only as long as needed to resolve your request. Please do not send files containing sensitive information unless we ask for them.

Apple may also provide us with aggregated, de-identified App Store statistics (and crash reports, only if you have chosen to share them with app developers in your device settings). These do not identify you to us.

---

## 8. Data Deletion

All data is stored locally or in your own iCloud account. You can delete individual files in the app and clear the preview cache in **Settings → Storage**.

**To delete all app data:**
iOS Settings → General → iPhone Storage → LokalTools → Delete App

This removes:
- All files stored in the app's "On This Device" storage
- Working copies, the preview cache, and the Share Import inbox
- Recent activity, favourites, Connected Folder bookmarks, pins, and preferences

**iCloud data (if used):**
Deleting the app does not remove files kept in its iCloud container. To remove them, delete them in the app before uninstalling, or go to iOS Settings → [your name] → iCloud → Manage Account Storage → LokalTools → Delete Data.

**Connected Folders:** files you saved to a connected folder stay in that folder; deleting the app does not remove them.

---

## 9. Children's Privacy

This app does not collect any information from any users, including children. It is not directed at children under 13.

---

## 10. Your Rights

Depending on where you live (for example under the EU/UK GDPR, the California Consumer Privacy Act, or the Personal Data Protection Acts of Malaysia or Singapore), you may have rights to access, correct, or delete personal data about you. Because the app sends us no data, the only personal data we may hold is support email correspondence. To make a request, email support@mlogictech.com.

---

## 11. Changes to This Policy

We may update this Privacy Policy to reflect changes in the app — for example if a subscription or advertising is added. The effective date at the top of this document will be updated accordingly, and material changes will also be noted in the App Store release notes. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## 12. Contact

If you have any questions about this Privacy Policy, please contact us:

**Email:** support@mlogictech.com
**Developer:** MLOGICTECH

---

*Privacy Policy URL: https://mlt-solutions.github.io/app-legal-docs/lokaltools/PRIVACY*
