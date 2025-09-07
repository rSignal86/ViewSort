# ViewSort – Your Digital QSL Card Sorter

## Download link: [Click here to download ViewSort](https://github.com/rSignal86/ViewSort/archive/refs/heads/main.zip)
Please remember that this is a zip file that you have to extract to a folder first before you can use it.

## ViewSort is a simple yet intelligent web tool built to help amateur radio operators efficiently sort their QSL cards before mailing them.  
It validates, organizes, and flags callsigns according to common QSL bureau rules. If you don't know how to sort QSL cards, ViewSort will do it for you.  
All you have to do is write the callsign into the program and note the number it gives you back on the card.  
When you're done, click "Start Sorting" and follow the numbers from top to bottom. The program will also tell you which cards require more attention.

> 🎉 **New "thing":** You can now generate a **PDF** with the sorted results – perfect for printing or archiving.

No installation required. Simply clone or download the repository and open the `ViewSort.html` file in your browser.
It is recommended to place ViewSort.html on your desktop.

Built with ❤️ by an amateur for an amateur, with help from AI.

---

# 🚀 Features
- Add and sort callsigns visually and interactively
- Automatic identification of country prefixes
- Built-in country database with sorting rules and QSL service info
- Assigns temporary numbers to each QSL card for manual sorting
- Warnings for excluded or unsupported QSL destinations
- **PDF generation** for sorted QSL list (new in GHv2.0)
- **StatPage PDF generation** for statistical overview of sorted cards (new in GHv3.4.0)
- Built-in interactive help with **voice guidance**
- Modular and expandable prefix system

# Requirements
- A PC that can run a modern browser like Microsoft Edge, google Chrome or Safari that is connected to internet, thats it :).

---

## 🛠️ How to Use
1. Open `ViewSort.html` in any modern web browser.
2. Type in callsigns (e.g. `LB6QJ`, `K5ABC`) and click "Add QSL Card".
3. Press **"Start Sorting"** or hit the **spacebar** to sort.
4. Cards will be organized by rules and flagged if:
   - The prefix is unrecognized
   - The country has no national QSL service or is not able to send QSL card for now
5. Press **"Generate PDF"** to view make a PDF file that has country lablel strips for you to print out and glow around the country stack you send.

---

## ♿ Accessibility
I do care deeply about inclusion. ViewSort is designed to be accessible for users with visual or hearing impairments:
- Interactive help via speech (Web Speech API)
- Clear visual indicators and contrast
- Simple layout optimized for screen readers

---

## 🔐 Privacy & GDPR Compliance

Your privacy is a priority for me. ViewSort is a **fully client-side tool** – all operations happen inside your browser.

- No accounts or sign-ins required  
- No cookies or tracking  
- No server communication or data collection  
- No data is stored or transmitted

✅ **This makes ViewSort fully GDPR compliant.**  
You can safely use it for personal use, clubs, or events without compromising anyone’s personal data.

---

## 🔧 Built With
- HTML5 / CSS3 / JavaScript
- Web Speech API (for voice assistance)
- jsPDF (for PDF export)
- AI-assisted development (with a little ham radio magic)

---

## 📦 Version History
- **GHv1.0** – Fully working prototype
- **GHv2.0** – Major update with:
  - PDF Export functionality
  - Modular prefix data system
  - Improved structure and maintainability
  - Accessibility and privacy improvements
- **GHv2.1.0**
  - Code cleanup
  - Repositioned buttons for better logic flow
  - Merged unsupported countries into a shared category to avoid political discrimination
- **GHv3.0.0**
  - Prefixes are now stored in an external JSON file for easier maintenance and updates, you do not need internet to support the sorting function
  - Added more shortcut keys to various buttons for improved usability
- **GHv3.4.0**
  - Added **StatPage PDF** generation feature for statistical overview of sorted QSL cards, it uses **F3** shortcut key

---

## 🔢 Version Number Format
Format: **Major.Minor.Patch**

Example: `2.5.1`  
- `2` = Major update (big new features or redesign)
- `5` = Minor update (added features or improvements)
- `1` = Patch (bug fixes or refinements)

---

_73 de LB6QJ_ ✨📡
