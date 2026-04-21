# Privacy Policy — Archive Duplicate Scanner

**Effective Date:** 1 May 2025  
**Developer:** MLOGICTECH  
**Contact:** support@mlogictech.com  
**App Website:** https://mlt-solutions.github.io/app-legal-docs/archiveduplicatescanner

---

## Summary

Archive Duplicate Scanner is a **fully offline, local-only** application. It does not collect, transmit, or share any personal data, usage data, or file content. Everything the app touches stays on your device.

---

## 1. Data We Do NOT Collect

We do not collect, store, or transmit:

- Personal information of any kind (name, email, location, etc.)
- File names, file contents, or file paths from your device
- Usage analytics, crash reports, or telemetry
- Device identifiers, IP addresses, or network information
- Perceptual hashes or scan results

---

## 2. Data Stored Locally on Your Device

The app creates the following files on your device for its own operation. These files never leave your device.

| File | Location | Purpose |
|------|----------|---------|
| `config.yaml` | App support directory | User preferences (theme, scan defaults) |
| `cache.db` | User-configurable (default `~/.archivescan/`) | SQLite hash cache for fast rescans |
| `file_index.db` | Same folder as `cache.db` | Stores scan session history and duplicate pair results |
| `trial.json` | `~/Library/Application Support/ArchiveScan/` (Mac) / `%APPDATA%\ArchiveScan\` (Windows) | Records first-launch date for trial management |

You can view, move, or delete any of these files at any time. Deleting them resets the corresponding feature (cache, sessions, or trial date).

---

## 3. Network Access

The app makes **no automatic network connections**. The only network activity occurs when you explicitly use these Help menu items:

- **Privacy Policy** — opens your default browser to this page
- **Terms of Service / EULA** — opens your default browser to the terms page
- **Report a Bug** — opens your default browser to the issue tracker

---

## 4. File Access

The app reads files in the folders you select for scanning. It:

- Reads archive files (CBZ, CBR, ZIP, RAR) to extract thumbnail images for hashing
- Reads image files (JPG, PNG, HEIC, WEBP, etc.) for perceptual hashing
- Moves files you explicitly mark for deletion to the system Trash / Recycle Bin

The app does **not** modify, upload, or copy your files. Only files you explicitly choose to trash are moved, and they go to the system Trash (recoverable).

---

## 5. Third-Party Libraries

Archive Duplicate Scanner is built on the following open-source libraries. None of these libraries perform any network requests or data collection when used within this app.

| Library | License | Purpose |
|---------|---------|---------|
| PySide6 (Qt for Python) | LGPL v3 | User interface framework |
| Pillow | HPND (MIT-compatible) | Image loading and processing |
| imagehash | MIT | Perceptual hashing algorithms |
| numpy | BSD 3-Clause | Numerical operations for hashing |
| rarfile | ISC | Reading RAR/CBR archive files |
| rapidfuzz | MIT | Fuzzy string matching for filename scan |
| PyYAML | MIT | Configuration file parsing |
| pillow-heif | MIT | HEIC/HEIF image format support |

Full license texts are included in the application bundle.

---

## 6. Platform Privacy Frameworks

**macOS:** This app complies with Apple's App Store privacy guidelines. It does not use any Apple privacy-sensitive APIs beyond user-selected file access.

**Windows:** This app complies with Microsoft Store policies and does not use any Windows data collection APIs.

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

*Privacy Policy URL: https://mlt-solutions.github.io/app-legal-docs/archiveduplicatescanner/PRIVACY*
