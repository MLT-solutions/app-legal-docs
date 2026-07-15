# Apple TV Privacy Policy — BiblioFuse Reader

**Effective Date:** 2026-07-15  
**Developer:** Modern Logic Tech Solutions (MLOGICTECH)  
**Contact:** support@mlogictech.com

## Summary

BiblioFuse for Apple TV is a companion app for privately streaming your personal
library from your Mac or Windows PC over your local network.

It is designed for CBZ/ZIP and CBR/RAR comic archives. The Apple TV app does not
upload your library to Modern Logic Tech Solutions, does not use advertising or
tracking SDKs, and does not collect analytics or telemetry.

## 1. Data We Do Not Collect

Modern Logic Tech Solutions does not collect, receive, store, sell, or share:

- Your book or comic files, page images, or thumbnails
- Your library titles, folders, tags, ratings, bookmarks, or reading progress
- Your App Lock PIN
- Your local IP address, device identifier, or network-discovery information
- Usage analytics, advertising identifiers, crash telemetry, or tracking data
- Payment-card or billing details

BiblioFuse for Apple TV does not create a BiblioFuse online account and does not send
your library activity to a developer-operated server.

## 2. Local-Network Streaming

When Streaming is enabled on your BiblioFuse Mac or Windows host, the Apple TV app:

- Uses Bonjour to discover that host on the same local network
- Requests library metadata, thumbnails, and individual archive page images from the
  host
- Sends reading progress, ratings, and tags back to that host when you use those
  features

This traffic stays between your Apple TV and your chosen Mac or PC on the local
network. The tvOS app uses local-network HTTP and does not use the BiblioFuse iCloud
streaming endpoint, Tailscale, or remote internet access. Use BiblioFuse streaming only
on a private network that you trust.

## 3. Data Stored on Apple TV

The app stores only the data needed to provide its Apple TV features:

| Data | Storage | Purpose |
|---|---|---|
| App preferences and reader settings | Apple TV app container | Remember display, navigation, filtering, and auto-scroll choices |
| Apple TV bookmarks | Apple TV app container | Reopen bookmarked pages |
| Temporary thumbnails and page data | Memory or system-managed cache | Display streamed library content without copying the whole library |
| Optional App Lock verifier | Apple Keychain | Verify the four-digit App Lock PIN without storing the PIN itself |
| Premium entitlement | Apple StoreKit | Determine whether streaming features are unlocked |

The App Lock stores a salted cryptographic verifier rather than the four-digit PIN.
Deleting and reinstalling the app removes its local bookmarks, preferences, caches,
and App Lock configuration.

## 4. Purchases

Premium purchases and subscription restoration are handled by Apple StoreKit and your
Apple ID. Modern Logic Tech Solutions does not receive your payment-card details.
Apple's handling of purchase information is governed by
[Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## 5. Third-Party Services

BiblioFuse for Apple TV does not integrate third-party advertising, analytics,
tracking, or crash-reporting SDKs. StoreKit and local-network frameworks are provided
by Apple. The archive and image-decoding libraries included in the app do not transmit
your library data to Modern Logic Tech Solutions.

## 6. Data Deletion

Reading progress, ratings, and tags written back to the host can be edited or removed
from your BiblioFuse library on that Mac or PC. To remove data stored by the Apple TV
app, delete BiblioFuse from Apple TV. You may then reinstall it without restoring the
previous local App Lock, bookmarks, settings, or cache.

## 7. Children's Privacy

BiblioFuse for Apple TV does not knowingly collect personal information from children
or any other users.

## 8. Changes to This Policy

We may update this policy when the Apple TV app's privacy practices change. The
effective date above will be updated when material changes are published.

## 9. Contact

For privacy questions, contact Modern Logic Tech Solutions (MLOGICTECH).

**Contact email:** support@mlogictech.com

**Privacy Policy URL:** https://mlt-solutions.github.io/app-legal-docs/bibliofuse/APPLE_TV_PRIVACY

**Last Updated:** 2026-07-15
