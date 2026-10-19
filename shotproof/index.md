---
title: Shotproof — Support & FAQ
---

# Shotproof

The work-photo camera that never loses a shot. Accurate address on every photo, zero ads, one-tap job reports.

## Support

Questions, feedback, or support requests: **[shubhamn910@gmail.com](mailto:shubhamn910@gmail.com)**

---

## Frequently Asked Questions

### Why does Shotproof save photos first before stamping?
Traditional camera apps can crash during stamping or image processing, losing your proof. Shotproof writes your untouched original photo atomically to secure storage immediately upon shutter press. Stamping occurs safely after. Even if the phone dies or the app closes, your photo is preserved.

### Does Shotproof work offline?
Yes. GPS coordinates, date, and local time work 100% offline. If cellular or Wi-Fi is unavailable at a rural job site, the photo is captured immediately with coordinates and marked "Address pending." When your phone regains connection, the street address is resolved and the stamp is automatically re-rendered.

### What is a Job Site and how does it make addresses accurate?
Standard phone geocoders can occasionally guess the wrong house number or adjacent parcel. In Shotproof, you can tap **Fix Address** to drop a pin on the exact building or entrance. Once saved as a Job Site, any photo taken within 150 meters automatically uses your verified address.

### Can I edit the address or note after taking a photo?
Yes. If you need to update a note or refine an address, you can edit it in the gallery. Because Shotproof preserves the original capture, it re-renders the stamped JPEG instantly.

### Will the stamp stay on my photos when moved to a PC or Mac?
Yes. Unlike apps that apply temporary metadata or iOS photo adjustments, Shotproof burns the stamp directly into a new, standard sRGB JPEG file. Opening the photo in Windows, Mac Preview, or third-party web portals displays the stamp permanently.

### Why does the camera make a shutter sound?
Apple iOS triggers a shutter sound unless the physical ring/silent switch on your device is set to silent. In certain regions (such as Japan and South Korea), local laws mandate that camera sounds always play.

### What does "Network-Verified Time" mean?
When online, Shotproof verifies the real UTC time from public time servers and ties it to hardware system uptime. If someone changes the device clock to falsify a timestamp, Shotproof detects the offset, stamps the true time, and notes the clock discrepancy in your job report.

### What are Independent Timestamp Certificates (RFC 3161)?
Shotproof Pro can send a cryptographic SHA-256 fingerprint (hash) of your photo to an independent public Time Stamping Authority (such as DigiCert or Sectigo). The authority signs a certificate proving that your exact photo existed at that precise second. You can verify this certificate independently on any computer using OpenSSL (`openssl ts -verify`).

### How do I restore my purchase?
Go to **Profile → Restore Purchases**. If you previously purchased a subscription with your Apple Account, it will activate immediately.

[Privacy Policy](privacy/)
