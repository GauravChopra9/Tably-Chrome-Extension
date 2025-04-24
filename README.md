# TabSaver – A Simple Chrome Extension for Saving URLs

**TabSaver** is a lightweight Chrome extension that allows users to save a list of URLs from the current tab and window. It stores the URLs in the browser's local storage, making them persist even after the browser or extension is closed. Users can also clear the saved list anytime with a single click.

---

## 🚀 Features

- ✅ Save the URL of the current tab
- ✅ Save all URLs from the current window
- ✅ Persist URLs using browser's local storage
- ✅ Clear all saved URLs with one click
- ✅ Interactive and minimal UI using DOM manipulation
- ✅ Built with HTML, CSS, and JavaScript

---

## 🧰 Tech Stack

- **HTML5** – For the extension popup structure
- **CSS3** – For styling the user interface
- **JavaScript** – Core logic and Chrome API integration
- **Chrome Extension API** – To access tabs and local storage

---

## 📦 Installation

To install the extension manually:

1. Clone or download this repository.
2. Open Google Chrome and go to `chrome://extensions/`.
3. Enable **Developer mode** (top-right toggle).
4. Click **"Load unpacked"** and select the project directory.
5. The extension will now appear in your Chrome toolbar.

---

## 🖼️ Screenshots

_Add screenshots here if you have any (e.g., popup interface, saved URLs list)._

---

## 🧠 How It Works

- When the extension is opened:
  - It uses the Chrome Tabs API to fetch the current tab or all tabs in the window.
  - URLs are stored in the browser’s local storage.
  - The DOM is dynamically updated to reflect the saved URLs.
- The “Delete” button clears all saved URLs from local storage and updates the view.

---

## 🔒 Permissions

This extension uses the following Chrome permissions:
- `tabs` – To access the current tab and window URLs
- `storage` – To store URLs locally

---

## 💡 Future Improvements

- Add the ability to name and organize saved URLs
- Support exporting/importing the saved list
- Add dark mode support
- Sync storage across devices

---

## 🙌 Acknowledgments

Thanks to the Chrome Extension API documentation and open-source community for guidance.

