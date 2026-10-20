---
title: "Privacy Policy"
layout: default
---

# Privacy Policy

**Effective Date:** 2026-04-18

**Last Updated:** 2026-10-19

Zeroneo Studio ("we", "us", or "our") operates **Cove Browser (Cove)**. This policy explains how the App handles information, including local storage, Apple iCloud, crash diagnostics and feedback.

## Summary

- No Cove account is required. We do not use advertising or cross-app tracking SDKs.
- Browsing history, website data and saved files are handled on your device. Bookmarks, home-page shortcuts and eligible open tabs can sync through your private Apple iCloud database, as explained below.
- Crash summaries are sent automatically by default after a crash report becomes available. You can turn this off in Settings → About.
- Feedback is sent only when you submit it. Crash summaries and feedback are delivered to our team through Feishu (Lark), a third-party service.
- We do not sell your information or use diagnostics and feedback for targeted advertising.

## Data on Your Device

Cove stores browsing history, cookies and website storage, tab sessions, saved files and their metadata, preferences, playback state and local diagnostic files to provide its features. The free video-save allowance and app-lock passcode are stored using the iOS Keychain. Local experience counters used to decide when to request an App Store rating are not sent to our team.

Private tabs are excluded from history and iCloud tab sync. Closing all private tabs clears their temporary website data. Files you deliberately save remain in your file library until you delete them. Private browsing does not make you anonymous to websites or your network provider.

## Apple iCloud and Backups

When iCloud is available to Cove, bookmarks and custom home-page shortcuts use a private CloudKit database associated with your Apple Account. Open non-private web tabs can also sync, including their URLs, titles and order, together with an app-generated device identifier and a device display name used to distinguish your devices. This is not an advertising identifier. These records are not sent to our feedback service.

In version 1.27.103, the in-app iCloud switch controls tab synchronization and which cross-device records are displayed. **Turning this switch off does not disable the underlying CloudKit storage for bookmarks and home-page shortcuts.** Use Cove's iCloud controls in iOS Settings to manage the App's access to iCloud. Turning synchronization off does not itself delete previously stored cloud records.

The current version stores browsing history and downloaded-file records locally rather than in CloudKit. History previously synced by older versions may remain in your iCloud storage. Saved files are not automatically uploaded by Cove's tab/bookmark synchronization. Device backups or files you export to other storage services are governed by your system settings and the services you choose.

## Crash Diagnostics

Apple MetricKit may deliver crash, performance and other diagnostic payloads. Cove stores these locally. At startup, it removes local payload files older than seven days; this is not a seven-day deletion guarantee for messages already sent to our team.

When automatic reporting is enabled and an unreported crash payload is available, Cove sends a summary through Feishu on a subsequent launch. Reporting is enabled by default and unsuccessful delivery may be retried on a later launch. The summary contains:

- App version and build number;
- iOS version and device model;
- the time the summary is prepared, not necessarily the time of the crash;
- the number of local crash payload files.

The summary does not include the full MetricKit payload, browsing history, URLs, search queries, saved files, an Apple Account, an advertising identifier or an app-generated device identifier. Our team uses it to investigate crashes and improve reliability. As with other internet requests, the receiving service processes connection information such as an IP address; we therefore do not describe this channel as absolutely anonymous.

You can disable **Auto-send Crash Diagnostics** in **Settings → About**. This stops future automatic summaries; it does not delete previously delivered messages or prevent local MetricKit storage. Manually submitted feedback is a separate choice.

## Feedback and Support

When you choose **Submit Feedback**, Cove sends your selected category, the text you enter, app version/build, iOS version, device model and submission time through Feishu to our team. If you include a webpage address, file name or contact detail, that information is included in your message. We do not automatically attach your browsing history, saved files or full diagnostic payloads. Avoid including passwords, authentication tokens or other sensitive information.

If you email us, we receive the email address and information you provide. We use feedback and support information to respond where contact details are available, troubleshoot issues and improve the App. A message can identify you if you include identifying details; it is not guaranteed to be anonymous.

## Services and Network Requests

- **Apple:** iCloud handles synchronization under your Apple Account. App Store purchases and subscriptions are processed by Apple; Cove uses StoreKit transaction information to determine access to Pro. We do not receive your payment-card details. Apple's own services and privacy practices also apply.
- **Feishu (Lark):** Receives and processes the crash summaries and feedback described above for delivery to our team. Messages are accessible to the team operating the feedback channel. They are not subject to the App's local seven-day diagnostic cleanup.
- **Websites and search providers:** Requests go to the sites or providers you choose. They may receive URLs, queries, cookies and connection information under their own policies. Cove's ad filtering does not prevent all website data collection.
- **Public rule and resource hosts:** Cove downloads filter rules and other public resources. The hosts receive normal connection information needed to serve requests. Cove does not attach your browsing history or saved files to filter-rule requests.
- **Safari content blocker:** Rules are supplied to Safari for local matching; this feature does not send Safari browsing history to our team.

These providers may process data in different countries according to their infrastructure and policies. We do not promise that every service stores information in your country.

## Permissions and App Lock

Camera access is optional and used to scan QR codes; Cove does not upload camera images through this feature. If you open a scanned URL, the destination receives an ordinary web request.

Face ID or Touch ID is optional for app unlock. Authentication is handled by iOS. Cove receives the authentication result, not your facial or fingerprint templates. The app-lock passcode is stored in the device's Keychain. Denying these permissions prevents the corresponding feature, not ordinary browsing.

## Retention, Deletion and Your Choices

- Clear history in the history view, manage website data with the App's cache/data controls, and delete saved files separately in the file library. Clearing history or cache does not erase all other categories of data.
- Manage synchronized records and backups through your Apple Account's iCloud storage settings. Deleting the App does not necessarily remove iCloud records, backups or Keychain items.
- We retain support messages and crash summaries as needed to investigate issues and provide support, subject to service retention and applicable requirements. There is no automatic seven-day expiry for these messages. To request access, correction or deletion of information you have sent us, email the address below and provide enough context to locate the message. Without an account or identifying details, we may be unable to identify an individual crash summary. We will explain any applicable limits rather than promise deletion of data we cannot locate or control.

## Children

Cove is a general-purpose browser and is not directed to children. Web content is outside our control. Follow the age rating and parental controls shown for your App Store region. If you believe a child has sent us personal information, contact us so we can investigate and address it.

## Saving Content

Only save content you own or have permission to save. Source restrictions and the App's domain restrictions still apply. See our [copyright policy](dmca-en.html) for copyright notices.

## Changes and Contact

We will update the date above when this policy changes and provide additional notice or seek consent where required.

For privacy questions or data requests: **kirakingdx@hotmail.com**.

This policy covers Cove, not the independent websites you visit or services you choose to use.
