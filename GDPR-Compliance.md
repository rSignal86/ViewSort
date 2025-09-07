# GDPR Compliance for ViewSort

**Effective Date:** [03 May 2025]

ViewSort is a client-side application designed for sorting amateur radio prefix codes in the user's browser. It prioritizes data privacy, transparency, and security, and fully complies with the General Data Protection Regulation (GDPR) (EU 2016/679).

---

## Data Collection

ViewSort **does not collect, store, or transmit** any personal data. All operations are performed **locally in the user's browser**. The data being processed (prefix codes) are not directly linked to individuals and are used solely for sorting purposes.

---

## Data Handling

ViewSort processes static JSON-based prefix information for sorting logic. The application includes a local export feature (PDF generation) that is performed entirely in the browser using `jsPDF`. No external calls are made, and no personal identifiers are included.

### External Components Used

#### GitHub
- Hosts the repository and static assets (HTML/JSON).
- Does not receive any personal data from ViewSort users.

#### jsPDF
- Used to generate PDF reports in-browser.
- No external communication or data storage occurs.

---

## Sub-Processors

While ViewSort does not transmit personal data, the following third-party services are involved in distribution or local operation:

- **GitHub** (hosting source code and JSON files)
- **jsPDF** (local library for PDF generation)

---

## Data Processing Agreement (DPA)

A full **Data Processing Agreement** is available as part of this repository to clarify the processing practices and responsibilities. You can find it here:

- `Data_Processing_Agreement.md` – Human-readable Markdown version

These documents outline the scope of processing, sub-processors, user responsibilities, and contact information.

---

## Contact

For privacy-related questions or requests, you may contact the project maintainer via the email address listed under callsign **LB6QJ** on [QRZ.com](https://www.qrz.com/).

---

[2025] ViewSort

