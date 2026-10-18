# Privacy Policy — LokalTools

**Effective Date:** 2026-10-18

**Developer:** MLOGICTECH

**Contact:** support@mlogictech.com

**App Website:** https://mlt-solutions.github.io/app-legal-docs/lokaltools

## Summary

LokalTools is an offline-first file workspace with PDF, image, video and file tools for iPhone and iPad. Tool processing takes place on your device. We do not receive your files, file names, passwords, scans or tool results, and there is no LokalTools account to create.

This policy covers both ad-free releases and releases with advertising enabled. In an advertising-enabled release, Google AdMob processes device, network, advertising and diagnostic information to serve and measure ads. An optional Apple subscription removes those ads. When advertising is disabled in a release, the app does not start the ad SDK or request ads and does not offer a new ad-free subscription. The plan shown in **Settings → Ad-Free** identifies the mode available in your version.

## 1. Your Files and On-Device Processing

PDF, image, video and file tools run on your device using local processing and Apple frameworks, including Vision, VisionKit, PDFKit, ImageIO and AVFoundation. We do not upload file content for processing or send it to the advertising provider.

The app reads files you select, share to it or make available through a folder you connect. Results are saved to the location you choose. If you choose iCloud Drive, a network folder, another storage provider or a sharing destination, that service may transfer the files under its own privacy policy. This is separate from tool processing.

Passwords entered for protected PDFs or archives are used on-device for the operation. They are not saved by LokalTools or sent to us or to the ad provider.

## 2. Data Stored on Your Device

| Data | Storage | Purpose |
|------|---------|---------|
| Imported, scanned, saved and generated files | App Documents folder, the app's iCloud Drive container, or a location you choose | Your files |
| Processing inputs and intermediate outputs | App container | Running tools and retaining working copies |
| Preview cache and Recent thumbnails | App container | Previews and Recent activity |
| Recent activity and favourites, including file names, actions, times and file-location references | On-device SwiftData database | Reopening, sharing and processing recent files |
| Connected Folder bookmarks and Quick Access pins | UserDefaults and the App Group container | Reopening folders you chose |
| Appearance, language and other preferences | UserDefaults | App settings |
| Subscription entitlement and ad cooldown state | On-device app state and preferences | Removing ads for subscribers and limiting ad frequency |
| Advertising consent choices, when advertising is enabled | Storage managed by Google's consent SDK | Remembering and applying privacy choices |

These local file records and preferences are not sent to MLOGICTECH. Google may process consent information as described in section 4. App-container data may be included in backups according to your Apple or computer backup settings.

### iCloud Drive and Connected Folders

Files in the LokalTools iCloud Drive container (`iCloud.com.mlogictech.lokaltools`) are kept in your own iCloud account. We have no access to that account. Apple's [Privacy Policy](https://www.apple.com/legal/privacy/) and [iCloud Terms](https://www.apple.com/legal/internet-services/icloud/) apply.

Connected Folders use Apple's Files picker and system folder bookmarks. Transfers to SMB servers and third-party providers are handled through the system or the provider. LokalTools does not receive or store the server or provider credentials you supply to Files. The provider's privacy policy applies to its transfers.

## 3. Apple Purchases

Where offered, **LokalTools Ad-Free** is an optional auto-renewable subscription purchased through Apple StoreKit. All tools remain free; the subscription removes the post-result advertising.

Apple handles payment. We do not receive your payment card, billing address or Apple ID. The app reads verified transaction information and subscription status on your device to provide, restore and manage the entitlement. LokalTools does not upload those StoreKit transactions to a developer-operated server. Apple handles its purchase records under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

Cancelling stops future renewal; the ad-free entitlement continues until the paid period ends. See our [Terms of Use](https://mlt-solutions.github.io/app-legal-docs/lokaltools/TERMS) for billing, cancellation and refunds.

## 4. Advertising and Consent

In advertising-enabled releases, free users may see a Google AdMob interstitial after a tool finishes and its result is available. Ads do not run the tools or receive their inputs or outputs. Ad availability varies. Active ad-free subscribers do not request or display ads; purchasing does not erase information the provider has already received.

LokalTools configures the Google Mobile Ads SDK to disable ad personalization. It does not request Apple's App Tracking Transparency permission or access the IDFA advertising identifier. **Non-personalized advertising still involves data processing.** Google and advertising partners involved in delivery may process:

- IP address and approximate location inferred from it; LokalTools does not request GPS location for ads.
- Device, app and network information, such as device model, operating-system version, app version and language.
- App- or developer-scoped identifiers used for advertising and measurement, distinct from IDFA.
- Ad requests, impressions, views, clicks and other ad-related interactions.
- Crash, performance and diagnostic information relating to the ad SDK.
- Consent status and privacy choices used to determine which requests are permitted.

These data support ad delivery, frequency control, measurement, fraud prevention and SDK diagnostics. LokalTools has no separate developer-operated analytics or crash-reporting service. AdMob can provide us with advertising reports. Google processes advertising data on its infrastructure, which may be outside your country, under its own retention practices and policies.

We do not provide Google or ad partners with your files, file names, paths, scans, photos, passwords, recognised text or tool results. We do not sell your file content or use it to target ads.

### Your choices

Google's User Messaging Platform checks consent requirements before the app requests ads. Where a consent message is required, it presents the applicable choices. The app requests ads only when the consent SDK reports that requests are permitted; this may permit limited or non-personalized ads depending on your choices and region. Refusing consent does not prevent you from using the tools.

When Google requires a privacy-options entry point, **Settings → Ad-Free → Ad Privacy Choices** lets you reopen the message and change your choices. This entry appears when required and advertising is enabled for you. An ad-free subscription stops subsequent ad requests. You can also use Google's privacy controls and contact us about your rights.

Learn more:

- [How Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites)
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google privacy controls](https://myadcenter.google.com/)

## 5. Device Permissions and Share Extension

LokalTools requests a permission when you use the feature that needs it. You can change permissions in iOS Settings.

| Permission or system picker | Use |
|-----------------------------|-----|
| Camera | Scanning documents and ID cards on-device |
| Photos, add only | Saving an image when you choose Save to Photos |
| System photo picker | Importing only the photos or videos you select |
| Files picker | Accessing only the files or folders you select |

The Share Extension copies selected files into the shared App Group container (`group.com.mlogictech.lokaltools`). The main app presents them in the Import Inbox so you can save or discard them. The extension does not include the advertising SDK and does not send shared files to an advertising service.

## 6. Network Access

File tools work locally. Network activity can occur for:

- iCloud Drive, connected network folders and storage providers you choose.
- Apple StoreKit product information, purchases, entitlement checks and restoration.
- Google consent messaging, ad requests, delivery, measurement and diagnostics when advertising is enabled for you.
- Opening legal pages, ad destinations or support email through the system. Contact Support opens your email app; it sends nothing until you send the message.

LokalTools does not operate a server that receives your files.

## 7. Support

If you email us, we receive your email address and the information you include. We use it to answer the request and retain it as needed for support and applicable obligations. Avoid sending sensitive files unless necessary.

Apple may provide aggregated App Store statistics and developer crash reports according to your Apple privacy settings. These are separate from Google's ad SDK diagnostics.

## 8. Deletion and Retention

You control files stored locally, in your iCloud account and in connected folders. Delete files in the app or Files, and clear the preview cache in **Settings → Storage**.

Deleting LokalTools through **iOS Settings → General → iPhone Storage → LokalTools → Delete App** removes its local files, working copies, caches, Recent database, Share Import inbox, bookmarks and preferences. It does not delete files in iCloud Drive, connected folders or other destinations. Delete those separately. Backups are managed through your backup provider.

Deleting the app does not cancel an Apple subscription or erase Apple's purchase records. Cancel subscriptions in **iOS Settings → [your name] → Subscriptions**. It also does not automatically erase information already received by Google. Google's retention and deletion controls apply to that information. Contact us for deletion of support correspondence, subject to applicable retention obligations.

## 9. Children's Privacy

LokalTools is a general-purpose utility and is not directed at children under 13. We do not knowingly request personal information from children. If you believe a child has supplied personal information to us, contact support@mlogictech.com so we can address it.

## 10. Your Rights

Depending on your location, you may have rights to access, correct, delete or restrict use of personal information, withdraw consent, object to processing, or complain to a privacy regulator. Contact support@mlogictech.com for requests about information held by MLOGICTECH. For information held by Apple, Google or a storage provider, use that provider's privacy controls or contact it directly. Changing advertising consent does not affect your access to the tools.

## 11. Changes and Contact

We may update this policy as the app or its data practices change. We update the effective date and communicate material changes through appropriate app or store notices. Where required, we will obtain consent before new processing begins.

**Email:** support@mlogictech.com

**Developer:** MLOGICTECH

*Privacy Policy URL: https://mlt-solutions.github.io/app-legal-docs/lokaltools/PRIVACY*
