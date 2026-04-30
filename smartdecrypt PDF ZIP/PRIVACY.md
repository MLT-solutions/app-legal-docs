# Privacy Policy — SmartDecrypt PDF ZIP

**Effective Date:** 2026-04-27
**Developer:** MLOGICTECH
**Contact:** support@mlogictech.com
**App Website:** https://mlt-solutions.github.io/app-legal-docs/smartdecrypt%20PDF%20ZIP

---

## Summary

SmartDecrypt PDF ZIP is a **privacy-first** application. It decrypts password-protected PDF, ZIP, and 7z files entirely on your device using a native Rust library. No files or passwords are ever transmitted to any server. The only data that leaves your device is Apple StoreKit purchase or trial entitlement information used to validate your access on your own Apple devices (iOS/macOS only).

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
| Trial entitlement | iOS/macOS: Apple StoreKit (synced via your Apple ID) | Tracks your 7-day free trial across your Apple devices |
| Trial counter | Windows: `%APPDATA%\SmartDecrypt\usage.json` | Tracks free trial usage (1-month trial) |
| License key | Windows: `%APPDATA%\SmartDecrypt\license.json` | Stores your purchased license key locally |

### Apple StoreKit (iOS & macOS)

The app uses **Apple StoreKit** to validate Premium purchases, restore purchases, and track your 7-day trial entitlement across your iPhone, iPad, and Mac when signed in to the same Apple ID.

- We do not receive your payment details
- StoreKit entitlement information is managed by Apple and is subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/)
- Purchase and trial restoration is handled through your Apple ID

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

- **iOS/macOS — StoreKit:** Apple StoreKit is used to validate your in-app purchase, restore purchases, and manage trial entitlement. This is handled entirely by Apple — we do not receive payment details.
- **Windows:** License keys are validated **offline** using a cryptographic signature (Ed25519). No network call is made for license validation.
- **Help links:** Tapping "Privacy Policy" or "Terms" in the app opens your browser to this page.

---

## 5. Platform-Specific Information

### iOS & macOS

- **Share Extension (iOS):** Files shared to SmartDecrypt via the iOS Share Sheet are processed in an extension sandbox. File data is not retained after decryption completes.
- **Keychain:** Passwords and profiles are stored in the iOS/macOS system Keychain, protected by your device's security (Face ID / Touch ID / password).
- **App Group:** The main app and Share Extension share data via the App Group `group.com.mlogictech.smartdecrypt`. This data remains on-device.
- **StoreKit entitlement:** Trial and purchase status are synced by Apple so your 7-day trial and Premium access are consistent across your Apple devices.
- **Purchase validation:** Handled by Apple StoreKit. We receive an anonymous receipt token only — no personal or billing information.

### Windows

- **Context Menu:** SmartDecrypt registers a right-click context menu entry. The app is invoked only when you explicitly right-click a file — it does not run in the background.
- **License key:** Your Paddle-issued license key is stored locally. It is validated offline using a cryptographic signature — no server call is made.
- **No advertisements:** The Windows version does not display any ads.

---

## 6. Third-Party Services

| Service | Platform | Purpose | Data Shared |
|---------|----------|---------|-------------|
| Apple StoreKit | iOS, macOS | In-app purchase and restore | Anonymous receipt token only |
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
