# Hafuh Layout Converter (v1.5.1)

Hafuh is a lightweight, privacy-focused, offline-first web application designed to correct text accidentally typed in the wrong keyboard layout (Hebrew to English or English to Hebrew). 

Whether you typed English with your keyboard set to Hebrew (e.g., `שפפךק` instead of `apple`) or Hebrew with your keyboard set to English (e.g., `gcrh,` instead of `עברית`), Hafuh instantly converts the text without requiring manual retyping.

---

## 🚀 Live Demo & Installation

You can access and install Hafuh directly from your browser:
**`https://YOUR_GITHUB_USERNAME.github.io/hafuh/`** *(Replace with your live GitHub Pages URL)*

---

## ✨ Features

- **Auto-Convert as You Type:** Automatically detects the input language and converts it in real-time as you type.
- **Auto-Copy with Configurable Delay:** Automatically copies the translated output to your clipboard once you stop typing. You can customize the delay duration (0.5s to 3.0s) via the interface settings.
- **Native Text-to-Speech (TTS):** Read your inputs or outputs aloud. It features automatic language detection and a dropdown selector to choose custom system voices installed on your device.
- **Live Text Statistics:** Real-time word and character counters displayed directly beneath each text area.
- **Flip Utility (Backward Hebrew Fix):** Reverses the character sequence of the text box. This is useful for correcting backward-running Hebrew pasted from legacy systems or poorly formatted PDFs.
- **Case Cycling:** Quickly cycle converted English text between lowercase, UPPERCASE, and Title Case.
- **Recent History Log:** Dynamically stores your last 5 conversions locally on the page for quick re-copying.
- **Quick Web Actions:** Dynamic one-click search on Google or translation on Google Translate (routes Hebrew text to English translation, and English to Hebrew).
- **Dark Mode:** A sliding theme toggle that preserves your preference (Light/Dark theme) across browser sessions.
- **Local Persistence:** All toggle preferences, voice selections, delay durations, and theme choices are stored locally using your browser's Local Storage.

---

## ⌨️ Keyboard Shortcuts

Hafuh supports standard system and application hotkeys to speed up your workflow:

* **`Ctrl + Left Shift`** (inside a text box): Force LTR (Left-to-Right) alignment.
* **`Ctrl + Right Shift`** (inside a text box): Force RTL (Right-to-Left) alignment.
* **`Ctrl + Enter`** (inside the input area): Manually force instant conversion, log to history, and copy to clipboard (if Auto-Copy is enabled).
* **`Esc`** (while focusing a text box): Instantly clears all text inputs, outputs, and running timers.

---

## 📲 PWA Installation Instructions

Hafuh is packaged as a **Progressive Web App (PWA)**, meaning it can be installed natively on desktop and mobile platforms and will work 100% offline.

### Desktop (Google Chrome, Microsoft Edge, Brave)
1. Open the live URL in your browser.
2. Click the **Install** icon (a monitor with an arrow) on the right side of the address bar.
3. The app will now launch in its own window and be pinned to your system's desktop/taskbar.

### iOS (Safari)
1. Open the URL in Safari.
2. Tap the **Share** icon at the bottom of the screen.
3. Scroll down and select **Add to Home Screen**.

### Android (Chrome)
1. Open the URL in Chrome.
2. Tap the three dots menu in the top-right corner.
3. Select **Install App** or **Add to Home Screen**.

---

## 🔒 Privacy & Security

Hafuh is entirely client-side. 
* No data, keystrokes, or clipboard contents are ever transmitted to an external server.
* All settings, themes, and history logs are processed and stored strictly on your local device.
* *Note: Clicking external web actions (Search on Google, Google Translate) will open standard outbound queries in a new browser tab.*

---

## 🛠️ Built With

* Vanilla HTML5
* Modern CSS3 (Variables & Animations)
* Pure client-side JavaScript (ES6+)
* Web Speech API (SpeechSynthesis)
* Service Worker API & Cache Storage API
