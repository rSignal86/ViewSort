# Data Processing Agreement (DPA) for ViewSort

**Effective Date:** [03 May 2025]

This Data Processing Agreement (DPA) governs the processing of data in connection with the use and development of **ViewSort**, a browser-based sorting utility for ham radio prefix data. The application is designed with a strong focus on **privacy, security, and transparency**, and does not collect or transmit personal data.

---

## 1. Purpose of the Agreement

This agreement outlines the responsibilities and obligations of contributors and users regarding the handling of any data processed by or in connection with ViewSort. It also ensures compliance with relevant data protection laws, including the **General Data Protection Regulation (GDPR)** (EU 2016/679).

---

## 2. Nature of the Data Processed

ViewSort performs **client-side sorting** of ham radio **prefix codes**. These prefixes are **not personally identifiable** and cannot be directly associated with any specific individual unless combined with external systems (e.g., QRZ.com). ViewSort does not request, store, or transmit any user-entered data.

No personal data is stored, logged, or sent to external servers.

---

## 3. Data Handling

ViewSort runs entirely in the user's browser. All sorting and data processing are performed **locally**, ensuring that data never leaves the user’s device. The following external components are involved:

- **Static JSON File**: The application may include a JSON file containing sorting rules or prefix data. This file contains no personal or identifiable information and is stored alongside the application source code on GitHub.
- **PDF Export (via jsPDF)**: When users choose to export results as a PDF, the file is generated entirely within their browser using the jsPDF library. No export or upload to external systems occurs.

### External Services and Libraries

#### a) GitHub  
GitHub hosts the ViewSort project repository and serves static assets like HTML, JavaScript, and JSON files. It acts as a **technical sub-processor** in the sense that it delivers application content to users. No data collected or processed by the application is sent to GitHub from end users.

GitHub’s own privacy and security policies apply, including compliance with:
- ISO/IEC 27001 certification
- EU-U.S. Data Privacy Framework

#### b) jsPDF  
jsPDF is a client-side JavaScript library used for generating PDF files in the user’s browser. It does not contact any external server or store any information. It operates fully offline and is included for transparency only, not as a data processor.

---

## 4. Sub-processors

ViewSort uses the following third-party components:

- **GitHub** – Hosting and distribution of application and assets.
- **jsPDF** – Local PDF generation library executed within the user’s browser.

No other sub-processors are used.

---

## 5. Security Measures

ViewSort is developed with a strong focus on **information security**. Measures include:

- Client-side only processing (no server-side logic)
- No use of cookies or tracking mechanisms
- No collection or storage of personal data
- Code is open-source and auditable by anyone

All development contributions are **limited to GitHub** to ensure traceability, transparency, and community oversight.

---

## 6. Contributions and Transparency

Developers may contribute to ViewSort **only via GitHub**, ensuring secure version control and public visibility of changes.

All users are encouraged to audit or suggest improvements to the code. For any questions about security or privacy, users are welcome to contact the maintainer via email found on **QRZ.com** (search for callsign: LB6QJ).

---

## 7. User Responsibility

ViewSort users are responsible for ensuring that the data they use with the application complies with their own local laws and organizational policies. This DPA does not cover any third-party integrations or platforms that users may choose to combine with the tool (e.g., QRZ.com, logging software, etc.).

---

## 8. Changes to This Agreement

This DPA may be updated to reflect changes in law or functionality. The current version will always be published in the GitHub repository.

---

## 9. Contact

For questions about this agreement, data handling, or security:

**Maintainer:** [LB6QJ - Tom]  
**Contact:** Via QRZ.com (Callsign: LB6QJ)

---

[2025] ViewSort.
