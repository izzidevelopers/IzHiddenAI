<div align="center">

# Iz Hidden AI

**An AI assistant desktop app by [Izzi Developers](https://github.com/izzidevelopers)**

_Invisible to screen recorders and capture tools. Ask anything, attach images and files, search the web, run terminal commands, build & download files, capture your screen, and talk to it with your voice._

![Iz Hidden AI Logo](https://clean-jere-aharpro-ce2ae165.koyeb.app/stream/1188?hash=3a562b)

---

**Platform:** 🪟 Windows only · 📲 Other platforms coming soon

</div>

---

## 📥 Download

- **File:** `Iz Hidden AI-Setup-1.1.0.exe`
- **Download size:** ~108 MB
- **Install size:** ~363 MB

> Download the latest version from the [Releases page](https://github.com/izzidevelopers/IzHiddenAI/releases).

## 🖥️ System Requirements

- **OS:** Windows 10 or newer (64-bit)
- **RAM:** Maximum 1 GB required (runs great on low-memory systems)
- **Processor:** Runs on CPUs less powerful than an Intel Core i3 — no high-end hardware needed
- **Disk space:** ~363 MB free space for installation

---

## 🆕 What's New in v1.1.0

- 🤖 **Agent mode — build & download files** — just ask the AI to create a script, app, HTML page or any file; it automatically opens a terminal sandbox, does the work, and hands you **download buttons** for every file it makes. A collapsible **Agent commands** panel shows (or hides) everything the agent is doing — live.
- ⚡ **Completely invisible** — the window is now removed from screen captures entirely with `WDA_EXCLUDEFROMCAPTURE`, not even a black box — and it stays invisible **even after hide/show** (`Ctrl + Shift + Space`).
- 🛠️ **Reliable startup** — fixed the Windows cache-lock crash (`Gpu Cache Creation failed`): single-instance lock, per-launch temporary cache, GPU shader disk cache disabled.
- 🔑 **Fully keyless** — chat, vision, voice transcription, web search and the agent all run on the free keyless **AharAPI** — no API keys needed anywhere.
- 🌐 **Smarter web search** — real-time search is now handled server-side (Google Custom Search) and always keeps sources in the answer.

---

## ✨ Features

- 💬 **Streaming AI chat** — instant streaming answers with a visible "thinking" phase
- 🤖 **Build & download files** — the AI uses its terminal sandbox to create scripts, apps or files and gives you **download buttons** for each one, with a live **Agent commands** panel
- 🌐 **Web search** — automatically fetches real-time information from the internet when asked
- 💻 **Run commands** — executes local terminal commands on your machine when you ask it to
- 🖼️ **Images & files** — attach screenshots, images, code and documents for the AI to analyze
- 🎤 **Voice input** — speak your questions; they are transcribed (AharAPI Whisper)
- 🔊 **Voice replies** — auto-reply voice mode reads answers aloud (TTS)
- 🖥️ **Window & screen capture** — snapshot any window, or transcribe its audio (meetings, videos)
- ✂️ **Screen crop** — crop any part of your screen and send it to the AI
- 🧠 **AI memory** — remembers important information about you across chats
- 📚 **Chat history** — all conversations are saved, searchable, and auto-titled
- ⚡ **Completely hidden from capture** — `WDA_EXCLUDEFROMCAPTURE` removes the window from recorders/shares entirely — no black box, even after hide/show
- ⌨️ **Global hotkey** — `Ctrl + Shift + Space` hides/shows the app from anywhere

---

## 🛠️ Tech Stack

- **Electron 43** — desktop shell (frameless, transparent window)
- **React 19 + TypeScript** — UI
- **Vite 8** — bundler / dev server
- **AharAPI** — free keyless OpenAI-compatible API: chat, streaming, tool calling, vision, audio transcription, and the autonomous agent (terminal sandbox + web search + file download links). No API keys are bundled or required.
- **koffi** — native FFI used for `SetWindowDisplayAffinity` (`WDA_EXCLUDEFROMCAPTURE`)
- **Capacitor 8** — Android/mobile support (via a browser shim)
- **electron-store** — persistent chat threads, memories, settings
- **react-markdown / remark-math / rehype-katex** — rich markdown + math rendering
- **framer-motion, lucide-react** — animations and icons

---

## 📦 How to Install

1. Go to the **[Releases page](https://github.com/izzidevelopers/IzHiddenAI/releases)** of this repository.
2. Download the **`Iz Hidden AI-Setup-1.1.0.exe`** file (~108 MB).
3. Double-click the downloaded installer.
4. Follow the on-screen instructions and wait for the installation to finish (takes about **363 MB** of disk space).
5. Launch **Iz Hidden AI** from your Start Menu or desktop shortcut.
6. The app opens as a hidden window — press **`Ctrl + Shift + Space`** to show it.

## ⚙️ How It Works

- **Chatting:** Type any question and press `Enter`. The AI streams its answer in real time with a visible "thinking" phase before replying.
- **Build & download files:** Ask the AI to build something (a script, an HTML page, a small app) and it automatically uses its sandboxed agent terminal, then shows **Download** buttons for the files it creates. The **Agent commands** panel shows what it's doing live.
- **Web search:** When a question needs live information, the AI automatically searches the internet (server-side Google Custom Search) and includes the results in its answer.
- **Run commands:** You can ask the AI to run local terminal commands, and it executes them on your machine and shows you the output.
- **Files & images:** Drag & drop, paste, or click the paperclip to attach screenshots, images, code, or documents for the AI to analyze.
- **Voice input:** Click the mic button and speak — your words are transcribed using AharAPI Whisper.
- **Voice replies:** Toggle the speaker button and the AI will read its answers aloud with TTS.
- **Window & screen capture:** Use the monitor button to pick a window — **Audio** transcribes its sound live (meetings, videos), **Snap** takes a screenshot.
- **Screen crop:** Use the scan button to crop any part of your screen and send it as an image.
- **Memory & history:** The AI saves important facts about you automatically and remembers them across chats. All conversations are saved, searchable, and auto-titled.
- **Privacy shield:** The window uses `WDA_EXCLUDEFROMCAPTURE` (Windows 10 2004+), so it is **completely invisible** in screen shares, recordings and screenshots — not even a black box, and it stays invisible even after you hide and show it. On older systems it falls back to `setContentProtection(true)` (black-box protection).

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| --- | --- |
| `Ctrl + Shift + Space` | Hide / show the app window (global) |
| `Enter` | Send message |
| `Shift + Enter` | New line |

---

## 💡 Usage Tips

- Drag & drop or paste files/images into the input box, or click the paperclip to attach.
- Use the scan button to crop any part of your screen and send it as an image.
- The monitor button lets you pick a window: **Audio** transcribes its sound live, **Snap** takes a screenshot.
- The mic button records your voice; toggle the speaker button for spoken replies.
- Ask it to build something — a script, an HTML page, a small app — and it will automatically use its sandboxed agent terminal, then show **Download** buttons for the files, no mode switching needed.
- The AI saves important facts to its memory automatically and can be asked to run terminal commands or search the web on demand.

---

## 🗺️ Roadmap

- 🪟 **Windows** — available now ✅
- 📲 **Other platforms** — coming soon

---

## 📄 License

[MIT](LICENSE) © 2026 [Izzi Developers](https://github.com/izzidevelopers)
