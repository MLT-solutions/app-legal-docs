# Privacy Policy — SmartDecrypt PDF ZIP

**Effective Date:** 2026-04-27
**Developer:** MLOGICTECH
**Contact:** support@mlogictech.com
**App Website:** https://mlt-solutions.github.io/app-legal-docs/smartdecrypt%20PDF%20ZIP

---

## Summary

SmartDecrypt PDF ZIP is a **privacy-first** application. It decrypts password-protected PDF, ZIP, and CBZ files entirely on your device using a native Rust library. No files or passwords are ever transmitted to any server. The only data that leaves your device is a small iCloud record used to sync your free trial status across your own Apple devices (iOS/macOS only).

---

## 1. Data We Do NOT Collect

We do not collect, store, or transmit:

- Personal information of any kind (name, email, location, etc.)
- The contents, names, or paths of files you decrypt
- Passwords or decryption keys you enter or store
- Usage analytics, crash reports, or telemetry
- Device identifiers, IP addresses, or network information

---

## 2. Data Stored on Your Device

The app stores the following data for its own operation.

| Data | Storage Location | Purpose |
|------|-----------------|---------|
| Password profiles (pattern → password mappings) | iOS/macOS: System Keychain + App Group container | Automatic file matching and decryption |
| Password profiles | Windows: `%APPDATA%\SmartDecrypt\profiles.json` | Automatic file matching and decryption |
| App preferences | iOS/macOS: App Group container (`group.com.mlogictech.smartdecrypt`) | Output folder, notification settings |
| App preferences | Windows: `%APPDATA%\SmartDecrypt\settings.json` | Output folder preferences |
| Trial start date | iOS/macOS: iCloud Key-Value Store (synced via your Apple ID) | Tracks your 30-day free trial across your Apple devices |
| Trial counter | Windows: `%APPDATA%\SmartDecrypt\usage.json` | Tracks free trial usage (1-month trial) |
| License key | Windows: `%APPDATA%\SmartDecrypt\license.json` | Stores your purchased license key locally |

### iCloud Key-Value Store (iOS & macOS)

The app stores a single value — your trial start date — in **iCloud Key-Value Store**. This is used solely to sync your 30-day free trial status across your iPhone, iPad, and Mac when signed in to the same Apple ID.

- We do not read, write, or access any other iCloud data
- This value is managed by Apple's iCloud infrastructure and is subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/)
- You can reset this by signing out of iCloud, but doing so will also reset your trial period

You can delete all app data at any time by uninstalling the app (see Section 7).

---

## 3. File Processing

SmartDecrypt processes files you open or share to it. It:

- Reads the encrypted file you select
- Attempts decryption using stored profiles or a password you enter
- Writes the decrypted output file to the same folder as the original (or your configured output folder)
- Does **not** modify or delete the original encrypted file
- Does **not** upload, transmit, or cache any file content

All decryption is performed by a native Rust library running entirely on your device.

---

## 4. Network Access

The app makes no automatic network connections to our servers. The only network activity is:

- **iOS/macOS — iCloud KV sync:** The trial start date is synced via iCloud Key-Value Store using Apple's infrastructure. This occurs automatically when iCloud is enabled.
- **iOS/macOS — StoreKit:** Apple StoreKit is used to validate your in-app purchase and restore purchases. This is handled entirely by Apple — we do not receive payment details.
- **Windows:** License keys are validated **offline** using a cryptographic signature (Ed25519). No network call is made for license validation.
- **Help links:** Tapping "Privacy Policy" or "Terms" in the app opens your browser to this page.

---

## 5. Platform-Specific Information

### iOS & macOS

- **Share Extension (iOS):** Files shared to SmartDecrypt via the iOS Share Sheet are processed in an extension sandbox. File data is not retained after decryption completes.
- **Keychain:** Passwords and profiles are stored in the iOS/macOS system Keychain, protected by your device's security (Face ID / Touch ID / password).
- **App Group:** The main app and Share Extension share data via the App Group `group.com.mlogictech.smartdecrypt`. This data remains on-device.
- **iCloud KV Store:** Trial start date is synced via iCloud so your 30-day trial is consistent across all your Apple devices. Requires iCloud to be enabled on your device.
- **Purchase validation:** Handled by Apple StoreKit. We receive an anonymous receipt token only — no personal or billing information.
- **Family Sharing:** The Premium upgrade supports Apple Family Sharing. If a family member purchases Premium, other family members can access it at no additional cost. Family membership is managed entirely by Apple.

### Windows

- **Context Menu:** SmartDecrypt registers a right-click context menu entry. The app is invoked only when you explicitly right-click a file — it does not run in the background.
- **License key:** Your Paddle-issued license key is stored locally. It is validated offline using a cryptographic signature — no server call is made.
- **No advertisements:** The Windows version does not display any ads.

---

## 6. Third-Party Services

| Service | Platform | Purpose | Data Shared |
|---------|----------|---------|-------------|
| Apple StoreKit | iOS, macOS | In-app purchase and restore | Anonymous receipt token only |
| Apple iCloud | iOS, macOS | Trial start date sync | One date value stored in iCloud KV; governed by Apple's Privacy Policy |
| Paddle | Windows | Payment processing at point of purchase | Handled by Paddle — we do not receive card details |

We do not use any analytics SDKs, advertising networks, or crash reporting services.

---

## 7. Data Deletion

Since all data is stored locally, you can remove it by uninstalling the app:

- **iOS:** Settings → General → iPhone Storage → SmartDecrypt → Delete App
- **macOS:** Drag SmartDecrypt from Applications to Trash; delete `~/Library/Group Containers/group.com.mlogictech.smartdecrypt/` to remove stored profiles
- **Windows:** Settings → Apps → Installed apps → SmartDecrypt → Uninstall; optionally delete `%APPDATA%\SmartDecrypt\` to remove profiles and license data

---

## 8. Children's Privacy

This app does not collect any information from any users, including children. It is not directed at children under 13.

---

## 9. Changes to This Policy

We may update this Privacy Policy to reflect changes in the app. The effective date at the top of this document will be updated accordingly. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## 10. Contact

If you have any questions about this Privacy Policy, please contact us:

**Email:** support@mlogictech.com
**Developer:** MLOGICTECH

---

*Privacy Policy URL: https://mlt-solutions.github.io/app-legal-docs/smartdecrypt%20PDF%20ZIP/PRIVACY*
