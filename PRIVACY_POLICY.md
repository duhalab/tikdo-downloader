# TikDo — Privacy Policy

**App name:** TikDo  
**Developer:** duhalab  
**Last updated:** September 6, 2026

---

## 1. Overview

TikDo is a TikTok video downloader app. It lets users paste a TikTok link, fetch video info, preview it, and download MP4/MP3 files to the device. This policy explains what the app accesses, what it stores, and what it does not do.

---

## 2. Data Collection & Storage

| Data | Purpose | Storage Location |
|------|---------|------------------|
| TikTok URLs entered by the user | Fetch video info & download | Temporarily in app memory; not uploaded to any server |
| Download history (creator, format, timestamp, cover URL) | Show History & re-download | Locally on device only via SharedPreferences |
| Favorites flag | Sort favorite downloads | Locally on device only |
| Thumbnails / cover images | Show preview in-app | Cached locally by cached_network_image |
| Clipboard content | Paste button convenience | Read only when user taps Paste; not stored |

**Important:** TikDo does **not** create accounts, does **not** send download history to any server, and does **not** share user data with third parties for advertising.

---

## 3. Permissions Used

- **Storage / Downloads:** To save MP4/MP3 files to your Downloads folder via the system downloader.
- **Internet:** To fetch video metadata and download files from TikTok CDNs.
- **Clipboard read (optional/on-demand):** Only when the user taps the Paste button or enables auto-paste.

---

## 4. Third-Party Services

- **TikTok:** The app fetches public TikTok video data. TikDo is not affiliated with TikTok/Bytedance.
- **Google Fonts:** Fonts served by Google Fonts API; standard font delivery service.
- **Flutter / Google Mobile Ads:** If ads are added in the future, their privacy policies will also apply.

---

## 5. Children's Privacy

TikDo is not directed to children under 13. If you are under 13, you may not use this app. We do not knowingly collect personal information from children.

---

## 6. Data Retention & Deletion

- All history and favorites are stored **only on the user's device**.
- Users can delete individual history items, remove favorites, or use "Clear all" to wipe local history.
- Uninstalling the app removes all locally stored data.

---

## 7. Security

The app operates locally where possible. Network requests use HTTPS. No user credentials are collected or transmitted.

---

## 8. Changes to This Policy

If the app's data handling changes, this policy will be updated with a new date. Users will be informed via app update notes or an in-app notice.

---

## 9. Contact

For privacy questions or requests, please open an issue on the [GitHub repository](https://github.com/duhalab/tikdo-downloader).

---

## 10. Play Store Compliance

This privacy policy is designed to meet Google Play Store requirements for data safety disclosures:

- ✅ Data is **not** collected or shared with third parties
- ✅ Files are saved **locally** to user's device
- ✅ Download history is **local-only** (SharedPreferences)
- ✅ Clipboard access is **user-initiated** (on-demand)
- ✅ No personal information is transmitted to external servers
- ✅ HTTPS is used for all network requests
