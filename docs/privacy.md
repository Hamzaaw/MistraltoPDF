

# Privacy Policy for **Mistral to PDF** Chrome Extension  
**Effective Date:** April 28, 2025

Thank you for using **Mistral to PDF**. We value your privacy and want to be completely transparent about our data practices.

---

## 1. Information We **Do Not** Collect  
**Mistral to PDF** is built around privacy. We **never** collect, store, track or transmit any personally identifiable information (PII) or the content of your Mistral AI conversations to any external servers.

---

## 2. What the Extension Accesses and Processes **Locally**  
To do its job, the Extension needs to read data only in your browser on the active `chat.mistral.ai` tab:

- **Chat Content**  
  - When you click **“Save as PDF”**, our content script reads the visible text, code blocks, HTML structure.  
  - **100% local**: formatted into PDF (or HTML/MD/JSON) and immediately downloaded.

- **Your Settings**  
  - Preferences (default filename, PDF orientation, compression) live in `chrome.storage.local`.  
  - Stored on your machine, governed by Chrome’s local-storage security. We **cannot** access these settings.

---

## 3. How Information Is Used  
- **Chat Content**: Only to generate the export file, entirely in your browser.  
- **User Settings**: Only to apply your chosen formatting options.

---

## 4. Data Storage & Security  
- **Chat Content**: Ephemeral—held only in memory while the export is created, then discarded.  
- **User Settings**: Persist in Chrome’s local storage. To erase, clear extension data via Chrome settings or uninstall the Extension.

---

## 5. Permissions We Request  
- **`activeTab`**: To read the current `chat.mistral.ai` page when you export.  
- **`storage`**: To save your export-settings locally.  
- **`downloads`**: To initiate the file download.  
- **Host permission** on `https://chat.mistral.ai/*`: So our content script can run there.

---

## 6. No Third-Party Data Services  
We don’t call out to any servers for your chat or settings. The bundled `html2pdf.bundle.min.js` library runs entirely in your browser.

---

## 7. Your Choices  
- Change settings anytime via the Extension popup.  
- Uninstall at any time via `chrome://extensions/`—this also clears your settings.

---

## 8. Changes to This Policy  
We may update this from time to time. If we do, we’ll update the **Effective Date** above and note any big changes. Check back here whenever you like.

---

## 9. Contact Us  
Questions or concerns? Shoot us an email at **hamzaw31@gmail.com**.
