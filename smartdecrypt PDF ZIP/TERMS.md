# End User License Agreement (EULA) — SmartDecrypt PDF ZIP

**Last Updated:** 2026-04-27
**Developer / Licensor:** MLOGICTECH
**Contact:** support@mlogictech.com
**App Website:** https://mlt-solutions.github.io/app-legal-docs/smartdecrypt%20PDF%20ZIP

---

## Apple App Store Notice (iOS & macOS)

For copies of this application obtained through the Apple App Store (iOS or macOS), the **Apple End User License Agreement (EULA)** governs your use of the application. The Apple EULA is available at:
https://www.apple.com/legal/internet-services/itunes/dev/stdeula/

Apple is not a party to this agreement and bears no responsibility for the application or its content.

**iOS & macOS — Free Tier and Premium Upgrade:**
The iOS and macOS versions are free to download. A **Premium upgrade (USD 9.99, one-time)** is available via in-app purchase, unlocking batch decryption and auto-cycle password features. The upgrade is a **non-consumable purchase** and supports **Apple Family Sharing** — one purchase covers all eligible family members. A **30-day free trial** of Premium is granted automatically on first launch. Trial status is synced across your Apple devices via iCloud Key-Value Store.

The sections below apply primarily to the **Windows version** sold directly.

---

## 1. Agreement

By downloading, installing, or using SmartDecrypt PDF ZIP, you agree to these terms. If you do not agree, do not install or use the application.

---

## 2. License Grant

Subject to your compliance with these Terms, MLOGICTECH grants you a **personal, non-exclusive, non-transferable, revocable license** to install and use SmartDecrypt PDF ZIP on Windows devices you own or control, for your personal or internal business use.

---

## 3. Pricing and Trial (Windows)

### 3.1 Free Tier

The Windows version is free to download and includes a **1-month free trial** of all features from the date of first launch. During the trial:

- All features are fully available (batch decryption, auto-cycle password, context menu, profiles)
- The trial start date is tracked locally on your device
- The trial is not server-validated and does not require an account

### 3.2 Purchase

After the trial period ends, a **one-time purchase of USD 9.99** is required to continue using all features.

- This is a **perpetual licence** — there are no subscriptions, recurring fees, or feature gates after purchase
- Payment is processed by the payment provider at the point of sale
- You will receive a **license key** by email after purchase
- Enter your license key in the app's Settings screen to unlock unlimited use

### 3.3 License Key Validation

License keys are validated **entirely offline** using a cryptographic signature (Ed25519). No network connection is required after you enter your key.

Your license key is stored locally on your device at `%APPDATA%\SmartDecrypt\license.json`.

### 3.4 Refunds

Refund requests are handled by the payment processor according to their refund policy. We do not process refunds directly.

To request a refund, contact us at support@mlogictech.com within 30 days of purchase.

---

## 4. Restrictions

You may not:

- Copy, redistribute, resell, sublicense, or transfer the application or your licence
- Reverse-engineer, decompile, or disassemble the application, except to the extent permitted by applicable law
- Remove, alter, or obscure any copyright notices or proprietary markings
- Share your license key with other users or use it on devices you do not own
- Use the application to decrypt files you do not have legal authorisation to access

---

## 5. Ownership

The application and all intellectual property rights therein are and remain the exclusive property of MLOGICTECH. These Terms do not transfer any ownership rights to you.

---

## 6. Open-Source Components

SmartDecrypt PDF ZIP is built on open-source components. Their respective licences govern your use of those components and are included in the application bundle.

| Component | Licence | Purpose |
|-----------|---------|---------|
| Rust standard library and crates | MIT / Apache-2.0 | Core runtime |
| pdfcpu | Apache-2.0 | PDF decryption |
| zip-rs | MIT | ZIP/CBZ decryption |
| windows-rs | MIT / Apache-2.0 | Windows API bindings |

Full licence texts are included in the application bundle.

---

## 7. File Operations — Important Disclaimer

**SmartDecrypt writes decrypted output files to your selected output folder.** Please note:

- The application does **not** delete or modify the original encrypted file
- Decryption may fail if the password is incorrect or the file is corrupt — in such cases no output is written
- **You are solely responsible** for verifying that you are authorised to decrypt any file you process
- **MLOGICTECH is not responsible** for any data loss, file corruption, or damage arising from use of the application

We strongly recommend keeping backups of any files before processing them.

---

## 8. Authorised Use

This application is intended for use on files you own or have explicit authorisation to decrypt. You must not use SmartDecrypt to circumvent copy protection, access files without permission, or violate any applicable law or third-party rights.

---

## 9. Disclaimer of Warranties

**THE APPLICATION IS PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT.**

MLOGICTECH does not warrant that the application will be error-free, uninterrupted, or successfully decrypt all files. Decryption success depends on the correctness of the password and the integrity of the source file.

---

## 10. Limitation of Liability

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL MLOGICTECH BE LIABLE FOR ANY INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL, OR PUNITIVE DAMAGES, INCLUDING LOSS OF DATA, LOSS OF PROFITS, OR BUSINESS INTERRUPTION, ARISING OUT OF OR IN CONNECTION WITH YOUR USE OF THE APPLICATION, EVEN IF MLOGICTECH HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

MLOGICTECH'S TOTAL LIABILITY TO YOU FOR ALL CLAIMS ARISING FROM OR RELATED TO THE APPLICATION SHALL NOT EXCEED THE AMOUNT YOU PAID FOR THE APPLICATION.

---

## 11. Indemnification

You agree to indemnify, defend, and hold harmless MLOGICTECH and its officers, directors, employees, and agents from and against any claims, damages, losses, and expenses (including reasonable legal fees) arising from your use of the application or your violation of these Terms, including any claim that files you decrypted were accessed without authorisation.

---

## 12. Updates

MLOGICTECH may release updates to the application from time to time. Updates may add features, fix bugs, or modify existing functionality. Your purchased licence entitles you to all future updates of the same major version at no additional cost.

---

## 13. Termination

**13.1 Your Right to Terminate**
You may stop using the application at any time by uninstalling it from your Windows device.

**13.2 Our Right to Terminate**
We reserve the right to revoke your license if you violate these Terms, particularly the restrictions in Section 4 or the authorised use provisions in Section 8.

**13.3 Effect of Termination**
Upon termination, your license ends immediately and you must uninstall the application from all devices. Your license key will be deactivated.

---

## 14. Governing Law

These Terms are governed by the laws of **Malaysia**, without regard to conflict-of-law principles. Any dispute arising from these Terms shall be subject to the exclusive jurisdiction of the courts of Malaysia.

---

## 15. Changes to These Terms

We may update these Terms from time to time. Changes will be effective when we update the "Last Updated" date at the top of this document. Continued use of the application after changes constitutes acceptance of the revised Terms.

---

## 16. Severability

If any provision of these Terms is found to be invalid or unenforceable, the remaining provisions shall remain in full force and effect.

---

## 17. Entire Agreement

These Terms, together with our Privacy Policy, constitute the entire agreement between you and MLOGICTECH regarding the Windows version of SmartDecrypt PDF ZIP.

---

## 18. Contact

For support, refund requests, or legal inquiries:

**Email:** support@mlogictech.com
**Developer:** MLOGICTECH

---

*Terms of Service URL: https://mlt-solutions.github.io/app-legal-docs/smartdecrypt%20PDF%20ZIP/TERMS*
