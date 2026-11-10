---
title: "Privacy Policy"
layout: default
---

# Privacy Policy

**Effective Date:** 2026-04-18

**Last Updated:** 2026-11-10

Zeroneo Studio ("we", "us", or "our") operates **Cove Browser (Cove)**. This policy explains how the App handles information, including local storage, Apple iCloud, crash diagnostics and feedback.

## Summary

- No Cove account is required. We do not use advertising or cross-app tracking SDKs.
- Browsing history, website data and saved files are handled on your device. Bookmarks, home-page shortcuts and eligible open tabs can sync through your private Apple iCloud database, as explained below.
- Crash diagnostic logs are sent only after you explicitly allow automatic diagnostics. You can withdraw this choice in Settings → About.
- The in-app email shortcut is currently hidden. You can contact our support address directly. Crash reports in version 1.27.111 use Google Firebase Crashlytics only after your separate permission.
- We do not sell your information or use diagnostics and feedback for targeted advertising.

## Data on Your Device

Cove stores browsing history, cookies and website storage, tab sessions, saved files and their metadata, preferences, playback state and local diagnostic files to provide its features. The free video-save allowance and app-lock passcode are stored using the iOS Keychain. Local experience counters used to decide when to request an App Store rating are not sent to our team.

Private tabs are excluded from history and iCloud tab sync. Closing all private tabs clears their temporary website data. Files you deliberately save remain in your file library until you delete them. Private browsing does not make you anonymous to websites or your network provider.

## Apple iCloud and Backups

When iCloud is available to Cove, bookmarks and custom home-page shortcuts use a private CloudKit database associated with your Apple Account. Open non-private web tabs can also sync, including their URLs, titles and order, together with an app-generated device identifier and a device display name used to distinguish your devices. This is not an advertising identifier. These records are not sent to our feedback service.

The in-app iCloud switch controls tab synchronization and which cross-device records are displayed. **Turning this switch off does not disable the underlying CloudKit storage for bookmarks and home-page shortcuts.** Use Cove's iCloud controls in iOS Settings to manage the App's access to iCloud. Turning synchronization off does not itself delete previously stored cloud records.

The current version stores browsing history and downloaded-file records locally rather than in CloudKit. History previously synced by older versions may remain in your iCloud storage. Saved files are not automatically uploaded by Cove's tab/bookmark synchronization. Device backups or files you export to other storage services are governed by your system settings and the services you choose.

## Crash Diagnostics

**Version transition:** The Firebase reporting and hidden in-app email shortcut described here apply to version 1.27.111. The currently distributed 1.27.103 uses the earlier MetricKit/Feishu (Lark) reporting channel, with automatic reporting enabled by default unless turned off in Settings → About. Updating does not transfer old reports to Firebase or reuse consent for the new recipient. Older versions may continue to send through the old channel until updated or disabled. Previously submitted reports and feedback may remain with the previous service; contact us about data requests.

Automatic crash reporting is off until you explicitly allow it. We ask once after onboarding and app unlock. Declining does not affect browsing or trigger repeated prompts. You can review the disclosure and allow reporting later in Settings → About. A previous default-on setting does not count as consent, and a previous explicit off choice remains off. A change of recipient requires an updated disclosure.

After permission, Cove starts Google Firebase Crashlytics to save crash reports on your device and submit them on a subsequent launch. We keep SDK automatic uploading disabled and make upload decisions from your saved choice. Failed submissions are managed by the SDK; availability requires the App to run and network access. First or renewed permission discards previous cached reports before allowing future reports to be sent. Historical MetricKit payloads from the old reporting channel are cleared locally and are not uploaded to Google or Feishu.

Crashlytics reports can include:

- crash time, app version/build, iOS version, device model and other technical device information;
- call stacks, binary names, UUIDs, addresses, offsets, exception classes/messages and signal details;
- Crashlytics installation UUIDs, Firebase installation IDs and session/report identifiers used to group reports and count affected installations;
- the version of the consent disclosure. We do not set a custom user ID.

We do not attach browsing history, webpage addresses, searches, saved-file names or contents, or feedback text to Crashlytics. We do not include Google Analytics, automatic screen-view breadcrumbs, advertising SDKs or cross-app tracking in this integration. System exception details may still contain additional context, so we do not promise that every report is free of identifying information. Google also processes connection information such as IP addresses.

Turn off **Auto-send Crash Diagnostics** in **Settings → About** to stop submitting new reports and request deletion of unsent reports. A running SDK may continue saving crash data locally until the App exits. Reports left from a withdrawn permission period are discarded before future uploads; this conservative cleanup can also discard some reports created after renewed permission. Reports already handed to the SDK may finish uploading or retry; this switch cannot recall them. This switch does not change Apple's system diagnostic settings. Email support is separate from this crash-reporting choice.

Local report storage is managed by Crashlytics, rather than the former MetricKit seven-day cleanup rule. Google's published policy says it retains crash traces and associated identifiers for 90 days before beginning removal from live and backup systems; it does not promise complete deletion exactly on day 90. Processing locations are governed by Firebase's applicable terms and infrastructure. See [Firebase privacy and security](https://firebase.google.com/support/privacy) for details. Our privacy contact below can receive requests about data we control.

## Feedback and Support

The in-app email shortcut is currently hidden. You can contact our support email below directly. If the shortcut is enabled in a future version, it opens your mail app with our support address and an editable draft containing the app version/build, iOS version, device model and draft creation time. You may edit or remove these details, add your message, and decide whether to send it. Cove does not send the email in the background or automatically attach browsing history, webpage addresses, saved files or full diagnostics. Avoid including passwords, authentication tokens or other sensitive information.

If you email us, we receive the email address and information you provide. We use feedback and support information to respond where contact details are available, troubleshoot issues and improve the App. A message can identify you if you include identifying details; it is not guaranteed to be anonymous.

## Services and Network Requests

- **Apple:** iCloud handles synchronization under your Apple Account. App Store purchases and subscriptions are processed by Apple; Cove uses StoreKit transaction information to determine access to Pro. We do not receive your payment-card details. Apple's own services and privacy practices also apply.
- **Google Firebase Crashlytics:** Processes crash reports and installation identifiers described above to help us diagnose crashes. Access is restricted to authorized project members. Google's data-processing terms, retention and deletion process apply.
- **Email services:** The mail app and providers you choose process feedback emails under their own terms. Our support mailbox receives the message and sender information when you send it. This version no longer submits feedback through Feishu (Lark); messages sent from older versions may remain in that service.
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
- We retain feedback messages as needed to investigate issues and provide support, subject to service retention and applicable requirements. Historical Feishu messages and support emails have no App-managed automatic seven-day expiry. Google's crash-report retention is described above. To request access, correction or deletion of information you sent us, email the address below with enough context to locate it. We may be unable to identify your data without locating information; we will explain applicable limits.

## Children

Cove is a general-purpose browser and is not directed to children. Web content is outside our control. Follow the age rating and parental controls shown for your App Store region. If you believe a child has sent us personal information, contact us so we can investigate and address it.

## Saving Content

Only save content you own or have permission to save. Source restrictions and the App's domain restrictions still apply. See our [copyright policy](dmca-en.html) for copyright notices.

## Changes and Contact

We will update the date above when this policy changes and provide additional notice or seek consent where required.

For privacy questions or data requests: **kirakingdx@hotmail.com**.

This policy covers Cove, not the independent websites you visit or services you choose to use.
