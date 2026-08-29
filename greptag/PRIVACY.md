# Privacy Policy — GrepTag

**Effective Date:** 2026-08-29
**Developer:** MLOGICTECH
**Contact:** support@mlogictech.com
**App Website:** https://mlt-solutions.github.io/app-legal-docs/greptag

---

## Summary

GrepTag is a **privacy-first** app for keyword-scanning and tagging your local TXT and EPUB book files. All scanning, tagging, and file management happens entirely on your device. No files, tags, or personal data are ever transmitted to our servers.

---

## 1. Data We Do NOT Collect

We do not collect, store, or transmit:

- Personal information of any kind (name, email, location, etc.)
- The contents of any book or document files you scan
- Your tags, ratings, keyword profiles, or search terms
- Usage analytics, crash reports, or telemetry
- Device identifiers, IP addresses, or network information

---

## 2. Data Stored on Your Device

The app stores the following data for its own operation.

| Data | Storage Location | Purpose |
|------|-----------------|---------|
| Book records (filename, file size, folder path, tags, rating) | SwiftData database in app container | Library management |
| Keyword profiles and keywords | SwiftData database | Grep scan configuration |
| Scan results | SwiftData database (cleared each session) | Display matched books |
| Lifetime scan count | UserDefaults (`NSUserDefaults`) | Free-tier usage tracking |
| Purchase entitlement | Apple StoreKit | Pro access status |

### iCloud Sync (Mac ↔ iOS)

If you use the Sync feature, the app writes library snapshots and copies book files to your personal iCloud container (`iCloud.com.mlogictech.bibliofusegreptagreader`). This data is:

- Stored in **your own iCloud account** — we have no access to it
- Governed by [Apple's iCloud Terms of Service](https://www.apple.com/legal/internet-services/icloud/)
- Encrypted by Apple both in transit and at rest
- Used only to transfer your files and metadata between your own devices

The SwiftData library database remains local to each device. Only sync snapshots (JSON) and book files are written to iCloud.

### Apple StoreKit

The app uses **Apple StoreKit 2** to validate Pro purchases and restore entitlements.

- We do not receive your payment details
- Purchase entitlement is managed by Apple and subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/)
- Restoration is handled through your Apple ID

---

## 3. File Access

GrepTag reads TXT and EPUB files you explicitly add to the library.

- **macOS:** Files are accessed at the paths you select. The app stores absolute file paths locally and does not copy files unless you use the "Send to iCloud Sync" or "Move to Folder" feature.
- **iOS:** Files are imported into the app's local Documents folder. You retain full control; the app does not upload them to any server.
- File content is read on-device solely to perform keyword scanning. Content is never cached beyond the scan session.

---

## 4. Third-Party Libraries

The app uses the following open-source libraries. Neither makes any network connections or collects any data.

| Library | Purpose |
|---------|---------|
| [ZIPFoundation](https://github.com/weichsel/ZIPFoundation) | Unpacking EPUB files (ZIP-based) for text extraction |
| [SDWebImageWebPCoder](https://github.com/SDWebImage/SDWebImageWebPCoder) | Decoding WebP cover images |

---

## 5. Network Access

GrepTag makes no automatic network connections to our servers. The only network activity is:

- **Apple StoreKit:** Purchase validation and entitlement restoration. Handled entirely by Apple.
- **iCloud (if Sync is used):** File transfers and snapshot sync via your personal iCloud account. We have no access to this data.
- **Help links:** Tapping "Privacy Policy" or "Terms" opens your browser to this page.

---

## 6. Data Deletion

All data is stored locally or in your own iCloud account. You can remove it by deleting the app.

**iOS:** Settings → General → iPhone Storage → GrepTag → Delete App

**macOS:** Delete the app from Applications. SwiftData is stored in `~/Library/Containers/com.mlogictech.bibliofusegreptagreader/`.

**iCloud data (if Sync was used):** Delete the `BiblioFuseGrepTagReader` folder from iCloud Drive in the Files app, or at [iCloud.com](https://www.icloud.com).

---

## 7. Children's Privacy

This app does not collect any information from any users, including children. It is not directed at children under 13.

---

## 8. Changes to This Policy

We may update this Privacy Policy to reflect changes in the app. The effective date at the top of this document will be updated accordingly. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## 9. Contact

If you have any questions about this Privacy Policy, please contact us:

**Email:** support@mlogictech.com
**Developer:** MLOGICTECH

---

*Privacy Policy URL: https://mlt-solutions.github.io/app-legal-docs/greptag/PRIVACY*
