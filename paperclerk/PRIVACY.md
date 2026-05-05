# Privacy Policy — PaperClerk

**Effective Date:** 2026-05-05
**Developer:** MLOGICTECH
**Contact:** support@mlogictech.com
**App Website:** https://mlt-solutions.github.io/app-legal-docs/paperclerk

---

## Summary

PaperClerk is a **privacy-first** document filing application. It uses Apple Intelligence to extract information from your documents — vendor, date, amount, document type — entirely on your device. No documents, filenames, or extracted data are ever transmitted to any server.

---

## 1. Data We Do NOT Collect

We do not collect, store, or transmit:

- Personal information of any kind (name, email, location, etc.)
- The contents, names, or paths of any documents you file
- Text extracted from your documents by OCR or AI
- Usage analytics, crash reports, or telemetry
- Device identifiers, IP addresses, or network information

---

## 2. Data Stored on Your Device

The app stores the following data for its own operation.

| Data | Storage Location | Purpose |
|------|-----------------|---------|
| Document records (vendor, date, amount, type, filename, SHA-256 hash) | SQLite database in app container or iCloud Drive | Filing history, search, duplicate detection |
| Filed document files | Local `Documents/` folder or iCloud Drive | Your organised documents |
| Filename templates and folder rules | SQLite database | Your custom filing preferences |
| Account aliases | SQLite database | Mapping account numbers to named groups |
| App preferences (date format, sync settings, etc.) | UserDefaults (`NSUserDefaults`) | App behaviour settings |
| Monthly extraction count | UserDefaults | Free-tier usage tracking (resets monthly) |
| Purchase entitlement | Apple StoreKit | Pro access status across your Apple devices |

### iCloud Sync (Pro feature)

If you enable iCloud sync, your document database and filed documents are stored in your personal iCloud Drive container (`iCloud.com.mlogictech.paperclerk`). This data is:

- Stored in **your own iCloud account** — we have no access to it
- Governed by [Apple's iCloud Terms of Service](https://www.apple.com/legal/internet-services/icloud/)
- Encrypted by Apple both in transit and at rest

### Apple StoreKit

The app uses **Apple StoreKit 2** to validate Pro purchases and restore entitlements across your Apple devices.

- We do not receive your payment details
- Purchase entitlement is managed by Apple and subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/)
- Restoration is handled through your Apple ID

---

## 3. Document Processing

PaperClerk processes documents you import or share to it. It:

- Reads the document (PDF or image) you select
- Extracts text using Apple's Vision framework (on-device OCR)
- Uses Apple Intelligence (FoundationModels, on-device) to identify vendor, date, amount, and document type
- Copies the file to your organised folder with your chosen filename template
- Stores a record (metadata only, not file content) in the local SQLite database
- Does **not** upload, transmit, or cache document content to any external server

All extraction is performed entirely on-device using Apple frameworks.

---

## 4. Share Extension

The iOS Share Extension (`com.mlogictech.paperclerk.ShareExtension`) allows you to file documents directly from other apps (Mail, Files, etc.).

- Files shared to PaperClerk are written to a shared inbox (`_Inbox/`) in the App Group container (`group.com.mlogictech.paperclerk`)
- The main app processes files from this inbox on next launch
- No shared data is transmitted outside the device

---

## 5. Network Access

PaperClerk makes no automatic network connections to our servers. The only network activity is:

- **Apple StoreKit:** Used to validate your Pro purchase or restore entitlements. Handled entirely by Apple — we do not receive payment details.
- **iCloud Drive (Pro, if enabled):** Document files and the database sync via your personal iCloud account. We have no access to this data.
- **Help links:** Tapping "Privacy Policy" or "Terms" in the app opens your browser to this page.

---

## 6. Data Deletion

All data is stored locally or in your own iCloud account. You can remove it by:

**To delete app data:**
iOS Settings → General → iPhone Storage → PaperClerk → Delete App

This removes:
- The SQLite database and all filing records
- All filed documents stored in the local app container
- App preferences and extraction count

**iCloud data (if sync was enabled):**
To remove documents from iCloud, delete the `PaperClerk` folder from iCloud Drive in the Files app, or sign in to [iCloud.com](https://www.icloud.com) → iCloud Drive → PaperClerk.

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

*Privacy Policy URL: https://mlt-solutions.github.io/app-legal-docs/paperclerk/PRIVACY*
