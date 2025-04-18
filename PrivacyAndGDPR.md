# Privacy and GDPR Compliance

_Last updated: April 18, 2025_

## Overview

ViewSort is a web-based tool designed for amateur radio operators to organize and sort QSL cards before mailing them.  
It operates entirely in the user's browser (client-side), without requiring any login, account creation, or external data processing.

---

## 🔐 Data Handling

ViewSort ensures full compliance with the **General Data Protection Regulation (GDPR)** by adhering to the following principles:

- **No personal data is stored or transmitted**.
- **No backend servers or APIs** are used.
- **No analytics or tracking tools** are included.
- **No cookies** are set or accessed.
- All user input (callsigns) remains local in your browser’s memory.
- When the browser is closed or the page is refreshed, all data is lost.

---

## 🌐 External Resources Used

Although ViewSort runs entirely in the browser, it makes use of the following third-party **client-side libraries and resources**:

### 1. Google Fonts
- **Resource:** `https://fonts.googleapis.com/css2?family=Inconsolata`
- **Purpose:** Provides the Inconsolata monospace font used in the user interface.
- **Privacy Impact:** Fonts are fetched from Google servers, which may log the IP address of the client.
- **GDPR Consideration:** This may be considered a transfer of personal data (IP address) to Google. To comply fully with GDPR, a local version of the font can be hosted instead.

### 2. jsPDF (PDF Generation)
- **Resource:** `https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js`
- **Purpose:** Enables client-side generation of PDF documents from the sorted output.
- **Privacy Impact:** Script is downloaded via CDN. No data is sent from the app to the jsPDF service.
- **GDPR Consideration:** CDNs may log IP addresses for security purposes. Consider self-hosting for maximum GDPR compliance.

### 3. Web Speech API
- **Resource:** Built-in browser feature (no third-party server).
- **Purpose:** Provides voice-based help and accessibility features.
- **Privacy Impact:** All synthesis happens locally within the browser. No data is transmitted to any server (browser dependent).
- **GDPR Consideration:** Generally safe, but always depends on the browser’s implementation and user settings.

---

## ✅ How to Use ViewSort in Full GDPR Mode

To run ViewSort with **maximum GDPR protection**, you may:
- Download and serve `ViewSort.html` locally or from your own server.
- Replace Google Fonts with a locally hosted version.
- Replace CDN-hosted jsPDF with a local copy of the `.js` file.
- Disable or avoid the voice help button if unsure about Web Speech API on your browser.

---

## Conclusion

ViewSort is designed with **privacy by default** in mind. No personal data is collected or stored, and all user activity stays in the browser unless the user explicitly exports data (e.g. via PDF).

> ⚠️ **Note**: If you embed ViewSort on a website or modify it to include online services, you may introduce GDPR-relevant considerations that are not part of the default version.

---

_73 de LB6QJ 🇳🇴_
