---
layout: default
title: Shotproof — Privacy Policy
permalink: /shotproof/privacy/
---

# Privacy Policy — Shotproof: Work GPS Camera

*Last updated: 18 November 2026*

At **Shotproof**, we respect your work and customer privacy. Your job site photos and coordinates belong strictly to your business.

---

### 1. Local Storage and Photo Processing
- All photos, stamped images, GPS coordinates, project tags, and notes are processed and stored locally on your device in the sandboxed App Group (`group.com.negishubham.shotproof`).
- We operate no cloud storage servers, accounts, or remote image databases.
- Photos and videos only leave your device when you export or share them via the iOS Share Sheet.

### 2. Network Requests, Location & Camera Permissions
- **Camera:** Used strictly to capture work photos and videos.
- **Microphone and speech recognition:** Used only while you record a video (sound for the clip) or hold the microphone button to dictate a note. Dictation uses on-device speech recognition only, so speech is never sent to Apple or anyone else, and it is not saved: only the text you dictate goes into the note. Video sound stays inside the video file on your device. Shotproof only uses the microphone during those moments; music and calls are not interrupted otherwise.
- **Address lookup:** When Shotproof resolves a captured coordinate or a typed job-site address, that coordinate or address is sent to Apple's geocoder. It is sent only when an address lookup is needed; Shotproof does not operate the service or send the photo, note, job, client, or timestamp certificate with it.
- **Network-verified time:** After a capture needs a time check, Shotproof makes an HTTPS `HEAD` request to Apple or, if unavailable, Cloudflare. No photo, hash, coordinate, address, job, client, note, or identity is placed in the request. As with any internet request, the destination receives connection metadata such as the device's public IP address.
- **Timestamp certificates:** For Pro users who leave timestamp certificates enabled, Shotproof sends an RFC 3161 request after each original and stamped photo is created. The request contains only that photo file's SHA-256 hash, protocol metadata, and a random non-identifying nonce. It is sent to DigiCert, Sectigo, or FreeTSA; the photo bytes, location, address, job, client, note, and identity are never sent. DigiCert and Sectigo currently publish only HTTP RFC 3161 endpoints; FreeTSA uses HTTPS. The returned signed certificate is stored beside the photo.
- Location and photo-hash requests are used only for app functionality, are not linked to an account, and are never used for tracking or advertising.

### 3. Local File Protection
- Originals, stamped photos, metadata, job/client records, and timestamp certificates use complete file protection (locked while your iPhone is locked) and are included in your encrypted iPhone backup (iCloud or computer), so a new or restored iPhone keeps your jobs. They remain available in Shotproof until you delete them or the app. Files you explicitly export are controlled by the destination you choose.

### 4. Zero Ads & Zero Tracking
- Shotproof contains **zero advertising SDKs** and zero analytics frameworks (`NSPrivacyTracking = false`).
- The App Store privacy label declares precise location and other user content used for app functionality, not linked to an account, and not used for tracking. These categories cover the address lookup and photo-hash timestamp requests described above.

### 5. Subscriptions & Payments
- Subscriptions to Shotproof Pro are processed directly by Apple via StoreKit 2.
- We never receive or store your billing or payment card credentials.

### 6. Contact
For privacy questions:
- **Developer:** Shubham Negi
- **Email:** [shubhamn910@gmail.com](mailto:shubhamn910@gmail.com)

[Back to Shotproof Home](/apps/shotproof/) · [Support & FAQ](/apps/shotproof/support/)
