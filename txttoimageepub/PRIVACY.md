# Privacy Policy — TXT to image EPUB

**Effective Date:** 18 September 2026
**Developer:** MLOGICTECH (Modern Logic Tech Solutions)
**Contact:** support@mlogictech.com
**App Website:** https://mlt-solutions.github.io/app-legal-docs/txttoimageepub

---

## Summary

TXT to image EPUB runs entirely on your own computer. There are no accounts, no
sign-up, no analytics and no servers belonging to us. We never receive your
documents, your images, your email address or your credentials.

The app does use the network, but only in two situations, and only because you
asked it to:

1. **Fetching pictures** that *your own document* refers to by link.
2. **Sending an EPUB by email**, if you set that feature up.

Both are described in full below.

---

## 1. Data We Do NOT Collect

We do not collect, store, receive or transmit to ourselves:

- Personal information of any kind (name, email address, location)
- The contents, names or paths of your files
- The links contained in your documents
- The images the app downloads
- Your email address, your recipient's address, or your mail password
- Usage analytics, crash reports or telemetry
- Device identifiers or IP addresses

The app has no "phone home" behaviour of any kind. We operate no server that
receives data from this app.

---

## 2. Data Stored Locally on Your Device

| File | Location | Purpose |
|------|----------|---------|
| `settings.json` | `%APPDATA%\TXT to image EPUB\` | Mail server settings, Kindle address, default recipient, attachment size limit, last used folder |

Your mail password is **not** written in readable form. It is encrypted with the
Windows Data Protection API (DPAPI) before being saved, which ties it to your
Windows user account on that machine — it cannot be read by another user or on
another computer. If DPAPI is unavailable, the password is simply not saved and
you will be asked for it each session.

This file never leaves your device. You may delete it at any time; the app will
recreate it with default values and ask you to re-enter your mail settings.

Books the app produces (`.epub` files) are written next to the source document
you converted, on your own disk.

---

## 3. Network Access — Downloading Pictures

When you convert a document, the app looks for image references inside **your
file** and retrieves them so the pictures can be stored inside the finished EPUB.

- The app **ships no links, no catalogue, no search and no list of websites.**
  It contacts only the addresses that already exist in the document you chose to
  convert, and it does so only when you press Execute or Recreate.
- Requests are ordinary web requests. They carry a standard browser user-agent
  string, an `Accept` header for images, and a `Referer` header derived from the
  address being requested. Your IP address is visible to the server you are
  contacting, exactly as it would be if you opened the same link in a browser.
- Each website you contact this way is an independent third party with its own
  privacy policy. We have no relationship with them, receive nothing from them,
  and cannot see what you requested.
- If your document refers to a Google Drive, Dropbox or OneDrive share link, the
  app rewrites it to that provider's direct-download address so the picture can
  be retrieved rather than the preview page. Your use of those services remains
  governed by their own privacy policies.
- Images referenced as files on your own computer are read from disk and involve
  no network activity at all.

**No conversion ever happens automatically.** Nothing is scanned or fetched on
launch; every scan and every download follows a button you pressed.

---

## 4. Network Access — Sending Email

The email features ("Send to Kindle" and "Email to") are **optional and off
until you configure them.**

When you use them:

- Your computer connects **directly** to the outgoing mail server *you*
  specified (for example your own Gmail or Outlook SMTP server) over an
  encrypted connection (implicit TLS or STARTTLS).
- Your message, your credentials and your attachments travel from your computer
  to your mail provider. **They never pass through us.** We have no mail server
  and no visibility into any message you send.
- Your mail provider, and the recipient's provider, handle the message under
  their own privacy policies.
- If you send to a Kindle address, Amazon receives the book and handles it under
  [Amazon's Privacy Notice](https://www.amazon.com/privacy). Amazon requires that
  your sending address be on your own Approved Personal Document E-mail List;
  that list lives in your Amazon account and we have no access to it.

You may clear your saved mail settings at any time from the settings dialog, or
by deleting `settings.json`.

---

## 5. File Access

The app reads and writes only where you point it:

- **Reads** `.txt` and `.epub` files in the folder you select (and its
  subfolders, if you tick that option).
- **Reads** image files on your computer when your document refers to them.
- **Writes** new `.epub` files next to the source document.
- **Deletes** files only when you explicitly select them and confirm the
  warning dialog. Deletion is permanent and is not sent to the Recycle Bin.

The app does not modify your source `.txt` files, and does not upload any of
your files anywhere except as an email attachment you explicitly send.

---

## 6. Third-Party Components

The app is built with the following open-source libraries. None of them collects
data or contacts any server on their own initiative.

| Library | Licence | Purpose |
|---------|---------|---------|
| Pillow | MIT-CMU (HPND) | Reading, converting and generating images |
| Requests | Apache 2.0 | Fetching pictures over HTTP(S) |
| urllib3 | MIT | HTTP transport used by Requests |
| certifi | MPL 2.0 | Root certificate bundle for TLS verification |
| charset-normalizer | MIT | Character-encoding detection |
| idna | BSD 3-Clause | International domain name handling |
| Python standard library (tkinter, smtplib, zipfile) | PSF Licence | Interface, mail transport, EPUB container assembly |

---

## 7. Children's Privacy

The app collects no information from anyone, including children, and is not
directed at children under 13.

---

## 8. Your Choices

- **Do not want any network activity?** Use documents that refer only to images
  already on your computer, and leave the email features unconfigured. The app
  is then entirely offline.
- **Want to remove saved mail settings?** Clear them in the settings dialog or
  delete `settings.json`.
- **Want to remove everything?** Uninstall the app and delete the
  `%APPDATA%\TXT to image EPUB\` folder.

---

## 9. Changes to This Policy

We may update this Privacy Policy as the app changes. The effective date above
will be updated accordingly. Continued use after a change constitutes acceptance
of the updated policy.

---

## 10. Contact

**Email:** support@mlogictech.com
**Developer:** MLOGICTECH (Modern Logic Tech Solutions)

---

*Privacy Policy URL: https://mlt-solutions.github.io/app-legal-docs/txttoimageepub/PRIVACY*
