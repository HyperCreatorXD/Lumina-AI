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
* **Persistent History**: Chat history (text-only) is saved to `localStorage`.
* **Customization**: Support for Light/Dark modes, custom AI names, and custom system prompts.

---

## 🚀 Deployment (GitHub Pages)

To host this for free on GitHub Pages:

1. **Get an API Key**: Obtain a key from [Google AI Studio](https://aistudio.google.com/).
2. **Configure Security**: 
   - Go to [Google Cloud Console](https://console.cloud.google.com/).
   - Navigate to **APIs & Services > Credentials**.
   - Edit your API Key and under **Website restrictions**, add your GitHub URL: `https://yourusername.github.io/*`.
3. **Insert Key**: In `script.js`, replace the `API_KEY` value with your restricted key.
4. **Push to GitHub**: Upload your files to a repository and enable **Pages** in the repository settings.

---

## 📜 License & Credit

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

**Requirements for Use:**
* **Attribution**: You must keep the original copyright notice and credit to **Dextrecs** in the source files.
* **Open Source**: If you modify or distribute this code, your version must also be released as open source under the same license.

---

## 🤝 Credits

Developed by **[Dextrecs](https://dextrecs.github.io/Dextrecs)**.

Forked by **HyperCreatorXD**.
