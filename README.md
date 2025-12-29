# 🌟 Lumina AI Chatbot
A sleek, **WhatsApp-style** web interface powered by the **Google Gemini API**. Lumina offers a familiar, responsive chat experience with support for media uploads, persistent history, and deep customization.

![License](https://img.shields.io/badge/license-GPL--3.0-green)
![JavaScript](https://img.shields.io/badge/ES6-JavaScript-yellow)
![CSS3](https://img.shields.io/badge/CSS3-WhatsApp--Style-blue)

---

## ✨ Features

* **WhatsApp UI/UX**: Includes a header with status indicators, chat bubbles with timestamps, and a responsive sidebar.
* **Gemini Integration**: Powered by the Google Generative AI SDK using the `gemini-2.5-flash` model.
* **Multimodal Support**: Capability to upload and process images, videos, and documents.
* **Persistent History**: Chat history (text-only) is saved to `localStorage`, allowing conversations to persist after page reloads.
* **Customization Engine**:
    * **Theme Toggle**: Support for both Light and Dark modes.
    * **AI Identity**: Users can change the AI's display name and profile picture URL.
    * **Custom System Instructions**: Option to set a "Custom Prompt" to change how the AI behaves.
* **Chat Management**: Features to download the chat history as a `.txt` file or clear the entire history.
* **Message Actions**: Long-press or right-click messages to copy text or remove specific bubbles from the view.

---

## 🚀 Getting Started

### 1. Prerequisites
You will need a Google Gemini API Key from Google AI Studio.

### 2. Setup
1.  Clone this repository or download the source files.
2.  Open `script.js`.
3.  Locate the `API_KEY` constant and replace the placeholder with your actual key:
    ```javascript
    const API_KEY = "YOUR_API_KEY_HERE";
    ```
4.  Open `index.html` in your browser.

---

## 🛠️ Built With

* **HTML5/CSS3**: Custom CSS variables for dynamic theming.
* **Vanilla JavaScript**: Modular JS using `importmap` for the Google AI SDK.
* **Google Generative AI**: The core intelligence for the chatbot.
* **Font Awesome**: High-quality icons for the interface.

---

## 📜 License

This project is licensed under the **GNU General Public License v3.0**.

## 🤝 Credits

Developed by **[Dextrecs](https://dextrecs.github.io/Dextrecs)**.

---

### ⚠️ Storage Notice
As noted in the application, images and videos are processed by the AI but are **not saved** to the local chat history to conserve browser storage space.
