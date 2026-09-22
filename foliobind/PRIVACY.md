# Privacy Policy — FolioBind: EPUB Studio

**Effective Date:** 22 September 2026
**Developer:** MLOGICTECH (Modern Logic Tech Solutions)
**Contact:** support@mlogictech.com
**App Website:** https://mlt-solutions.github.io/app-legal-docs/foliobind

---

## Summary

FolioBind: EPUB Studio runs entirely on your iPhone or iPad. There are no
accounts, no sign-up, no analytics and no servers belonging to us. We never
receive your documents, your images, or your credentials.

The app does use the network, but only in the following situations, and only
because you asked it to:

1. **Fetching pictures** that *your own document* refers to by link.
2. **Sharing or emailing an EPUB**, through Apple's system share sheet or Mail
   composer.
3. **Checking or completing an App Store purchase**, through StoreKit.

Each is described in full below.

The app performs conversion of TXT, Markdown, DOCX, fixed-layout PDF, CBZ, ZIP
image archives, and CBR sources, plus EPUB editing, entirely on-device. It
does not use a developer-operated server, account, analytics, or advertising
SDK.

---

## 1. Data We Do NOT Collect

We do not collect, store, receive or transmit to ourselves:

- Personal information of any kind (name, email address, location)
- The contents, names or paths of your files
- The links contained in your documents
- The images the app downloads
- Your email address or your recipient's address
- Usage analytics, crash reports or telemetry
- Device identifiers or IP addresses

The app has no "phone home" behaviour of any kind. We operate no server that
receives data from this app.

---

## 2. Data Stored Locally on Your Device

The app writes generated books to its app Documents/Generated folder and
keeps overwrite backups in Documents/Backups. Files staged for conversion or
imported for editing are held in Documents/Incoming until you use them; once a
staged file has produced its EPUB, that copy is deleted automatically, and you
can clear anything left over from Settings. Preview extraction is disposable
cache data, also clearable from Settings.

When you select an external folder, iOS supplies a security-scoped bookmark
so the app can access that folder again; the bookmark remains on the device
and can be disconnected in Settings. Files shared from another app pass
through a private App Group inbox and are removed once consumed.

None of this data leaves your device. Uninstalling the app removes all of it.

---

## 3. Network Access — Downloading Pictures

When you convert a document, the app looks for image references inside **your
file** and retrieves them so the pictures can be stored inside the finished
EPUB.

- The app **ships no links, no catalogue, no search and no list of
  websites.** It contacts only the addresses that already exist in the
  document you chose to convert, and it does so only when you start a
  conversion.
- Requests are ordinary web requests. They carry a standard user-agent string
  and an `Accept` header for images. Your IP address is visible to the server
  you are contacting, exactly as it would be if you opened the same link in a
  browser.
- Each website you contact this way is an independent third party with its
  own privacy policy. We have no relationship with them, receive nothing from
  them, and cannot see what you requested.
- If your document refers to a Google Drive, Dropbox or OneDrive share link,
  the app rewrites it to that provider's direct-download address so the
  picture can be retrieved rather than the preview page. Your use of those
  services remains governed by their own privacy policies.
- Images referenced as files already on your device are read locally and
  involve no network activity at all.

**No conversion ever happens automatically.** Nothing is scanned or fetched
on launch; every scan and every download follows an action you took.

---

## 4. Network Access — Sharing and Purchases

**Send to Kindle** and **Mail** are optional actions you trigger explicitly.
Send to Kindle opens Apple's system share sheet so you can choose the Kindle
app or another installed destination. Mail opens Apple's standard Mail
composer with the selected EPUB attached. Delivery is handled by the account
configured in Mail, or by the app selected from the share sheet — the app
does not receive, store, or transmit any mail account password.

Amazon, the Kindle app, Apple Mail, and other share destinations are
independent third parties. Their own size, sender-approval, account, and
delivery rules apply. If you send to a Kindle address, Amazon receives the
book and handles it under [Amazon's Privacy Notice](https://www.amazon.com/privacy);
Amazon documents EPUB support up to 200 MB for its wireless Send to Kindle
service.

The app uses Apple StoreKit to display App Store pricing, determine verified
Pro entitlements, make or restore a purchase, and open Apple's
subscription-management screen. Apple processes those requests under its own
privacy terms. MLOGICTECH does not receive or store payment-card or App
Store account credentials. The app stores only its local entitlement/
allowance state needed to apply the free daily output limit.

---

## 5. File Access

The app reads and writes only where you point it:

- **Reads** `.txt`, `.md`, `.docx`, `.pdf`, `.cbz`, `.zip`, `.cbr`, and
  `.epub` files you choose through Files, Open In, or the share sheet, and
  their subfolders if you enable that option for a selected folder. It does
  not scan other folders automatically.
- **Reads** image files on your device when your document refers to them.
- **Writes** new `.epub` files to the app's Documents/Generated folder.
- **Deletes** files only when you explicitly select them and confirm the
  warning dialog. Deletion is permanent.

The app does not modify your source files, and does not upload any of your
files anywhere except through the system share sheet or Mail composer you
explicitly invoked.

---

## 6. Third-Party Components

The app is built with the following open-source libraries. None of them
collects data or contacts any server on their own initiative.

| Library | Licence | Purpose |
|---------|---------|---------|
| ZIPFoundation 0.9.20 | MIT | EPUB and DOCX ZIP container access |
| libarchive-swift (libarchive) | BSD 2-Clause / upstream notices | CBR/RAR archive reading |
| SwiftyOpenCC | MIT / upstream notices | Offline Simplified/Traditional Chinese conversion |
| SDWebImage 5.21.7 | MIT | Image decoding and transformation |
| SDWebImageWebPCoder 0.15.0 / libwebp | MIT / BSD-style upstream notices | WebP decoding and encoding |

---

## 7. Children's Privacy

The app collects no information from anyone, including children, and is not
directed at children under 13.

---

## 8. Your Choices

- **Do not want any network activity?** Use documents that refer only to
  images already on your device. The app is then entirely offline.
- **Want to reclaim storage?** Settings has dedicated buttons to clear
  generated books, overwrite backups, imported/staged files, and the preview
  cache, each behind its own confirmation.
- **Want to remove everything?** Uninstall the app.

---

## 9. Changes to This Policy

We may update this Privacy Policy as the app changes. The effective date
above will be updated accordingly. Continued use after a change constitutes
acceptance of the updated policy.

---

## 10. Contact

**Email:** support@mlogictech.com
**Developer:** MLOGICTECH (Modern Logic Tech Solutions)

---

*Privacy Policy URL: https://mlt-solutions.github.io/app-legal-docs/foliobind/PRIVACY*
