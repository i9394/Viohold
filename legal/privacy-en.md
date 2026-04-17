# Privacy Policy

**Effective Date:** 2026-04-18
**Last Updated:** 2026-04-18

Zeroneo Studio ("we", "us", or "our") operates the **Halcyon** mobile application (the "App"). This Privacy Policy explains how we handle information when you use the App.

## Summary

- **We do not collect, transmit, or share any personal information.**
- All browsing history, bookmarks, downloaded files, and settings stay on your device.
- We have no servers receiving user data.
- The App does not contain third-party analytics, tracking SDKs, or advertising networks.

## Information Stored Locally on Your Device

The following data is stored **only on your device** and never transmitted to us or any third party:

| Data | Purpose | Storage |
|---|---|---|
| Browsing history | In-app history view | SwiftData (local SQLite) |
| Bookmarks | User bookmarks | SwiftData (local) |
| Open tabs | Tab session persistence | Local JSON |
| Downloaded files | File management | App sandbox |
| Cookies | Web browsing session | WKWebView managed, sandboxed |
| App settings | User preferences | iOS UserDefaults |
| Passcode / biometric | App lock | iOS Keychain + Face ID authentication |

You can delete all locally stored data at any time via the App's **Settings → Clear Cache** and **History → Clear All**, or by uninstalling the App.

## Permissions

The App requests the following iOS permissions, all used **only on your device**:

| Permission | Purpose | Required? |
|---|---|---|
| Camera | Scanning QR codes to open URLs (the camera output is processed locally, not uploaded) | Optional |
| Face ID / Touch ID | Unlocking the App when App Lock is enabled | Optional |
| Photos (save only) | Saving downloaded images to Photos when user explicitly requests | Optional |

Denying any permission does not restrict other App functionality.

## Third-Party Content and Services

- **Web pages you visit**: The App is a web browser. Any website you visit may collect information about you according to its own privacy policy — we have no control over third-party websites.
- **Ad-blocking rule lists**: The App periodically downloads public rule lists (Peter Lowe's list, EasyList China) from `pgl.yoyo.org` and `easylist-downloads.adblockplus.org` to update ad filters. These are **one-way downloads of public rule files**; no user data is sent.
- **Safari Content Blocker Extension**: Rule lists are shared with the system Safari browser via an iOS App Group container (`group.com.cnkira.bbrowser`). Data stays on your device.

## Data We Do NOT Collect

- Your personal information (name, email, phone number, address).
- Your location (the App does not request location permission).
- Your device identifier (IDFA / IDFV).
- Your browsing activity, search queries, or tab contents.
- Any analytics or crash reports.

## Children's Privacy

The App is rated **17+** (App Store age rating) due to unrestricted web access. We do not knowingly collect any data from users under 17.

## Copyright and Media Downloading

The App allows saving web page resources for offline access, similar to common web browser features such as Safari's "Add to Reading List" or built-in download managers. Users are responsible for respecting copyright law when saving content.

We maintain a **domain blocklist** that prevents media detection on major platforms (YouTube, Netflix, TikTok, Instagram, Facebook, Twitter, Bilibili, iQiyi, Spotify, Apple Music, and others). See `dmca-en.md` for the copyright infringement notification process.

## Changes to This Policy

We may update this Privacy Policy from time to time. The "Last Updated" date will reflect the latest revision. Continued use of the App after changes means acceptance of the updated policy.

## Contact

For privacy questions or data deletion requests:

**Email:** kirakingdx@hotmail.com

---

*This Privacy Policy applies only to the Halcyon mobile application. It does not apply to third-party websites you visit through the App.*
