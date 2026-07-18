# ⚡ CPY

### One Click and Download

**Select. Grab. Export. — 100% offline, no cloud, no tracking.**

![Chrome](https://img.shields.io/badge/Chrome-supported-4285F4?logo=googlechrome&logoColor=white)
![Firefox](https://img.shields.io/badge/Firefox-supported-FF7139?logo=firefoxbrowser&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest-V3-6366F1)
![Offline](https://img.shields.io/badge/100%25-Offline-10B981)
![License](https://img.shields.io/badge/license-MIT-64748B)

<p align="center">
  <img src="vid_01.gif" alt="CPY demo" width="600">
</p>

<p align="center">
  <img src="pic_01.png" alt="CPY popup screenshot" width="700">
</p>

---

## ✨ What is CPY?

**CPY** is a lightweight Chrome & Firefox extension that lets you select any text on the web and save it with a single click. Every saved snippet is stored locally on your device, and you can export your whole collection anytime as **JSON, CSV, TXT, or PDF** — no account, no server, no internet required after install.

Perfect for researchers, students, and anyone who copies AI answers, articles, or reference material from multiple tabs and wants it organized in one clean, exportable dataset.

---

## 🚀 Features

| | |
|---|---|
| 🖱️ **One-click grab** | Select any text → a floating bubble appears → click to save |
| 💾 **Local-first storage** | Everything stays in your browser's local storage — nothing leaves your device |
| 📄 **4 export formats** | JSON, CSV, TXT, and PDF — all generated fully offline |
| 🧼 **Smart cleanup** | Auto-removes messy line breaks, stray quotes, and exact duplicates |
| 🌐 **Cross-browser** | One codebase, works natively on both Chrome and Firefox |
| 🔒 **Privacy by design** | No analytics, no external requests, no permissions beyond local storage |

---

## 🧭 How It Works

```
Select text on any page
        ↓
   ⚡ bubble appears
        ↓
   Click to save locally
        ↓
Open the CPY popup → Export as JSON / CSV / TXT / PDF
```

Everything happens inside your browser. No data is ever sent anywhere.

---

## ✅ Where CPY Works

- Any regular website — blogs, docs, news, articles
- AI chat platforms — ChatGPT, Gemini, Claude, and similar
- Any `http://` or `https://` page with real, selectable text

## ❌ Where CPY Can't Work (Browser Limitations)

These aren't bugs — browsers deliberately block **all** extensions from running here, by design:

| Location | Why |
|---|---|
| Browser's built-in PDF viewer (`file:///…pdf`) | Runs in a privileged internal page extensions can't access |
| `chrome://`, `about:`, `view-source:` pages | Reserved browser UI, off-limits to extensions |
| Google Docs / Sheets / Slides | Renders content on `<canvas>` instead of real HTML text, bypassing the browser's native selection entirely |

**Workaround for PDFs:** open the file in a regular HTML-based web PDF viewer instead of the browser's native one, so it loads as a normal webpage.

---

## 🕐 When to Use CPY

- Collecting AI-generated answers into a clean dataset
- Saving research snippets from multiple articles/tabs
- Building a quick offline knowledge base without copy-pasting into a doc manually
- Exporting a reading session as PDF/TXT to review later, fully offline

---

## 🤝 Contributing

Contributions are very welcome!

- 🐛 Found a bug or have a feature idea? Open an issue or send a **pull request**
- 🤝 Want to collaborate or partner on this project? Email me directly:

  **📧 tohidul07890@gmail.com**

- ⭐ If CPY is useful to you, please **star the repo** — it genuinely helps
- 💬 Feedback, suggestions, and criticism are always appreciated

---

## 📜 License

MIT — free to use, modify, and distribute.

---

**Made with ⚡ for people who hate losing good text.**
