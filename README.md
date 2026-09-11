<div align="center">

# Iz Hidden AI

**An AI assistant desktop app by [Izzi Developers](https://github.com/izzidevelopers)**

_Invisible to screen recorders and capture tools. Ask anything, attach images and files, search the web, run terminal commands, build & download files, capture your screen, and talk to it with your voice._

![Iz Hidden AI Logo](https://clean-jere-aharpro-ce2ae165.koyeb.app/stream/1188?hash=3a562b)

---

**Platform:** ðŸªŸ Windows only Â· ðŸ“² Other platforms coming soon

</div>

---

## ðŸ“¥ Download

- **File:** `Iz-Hidden-AI-Beta-Setup-1.2.0.exe`
- **Download size:** ~108 MB
- **Install size:** ~421 MB

> Download the latest version from the [Releases page](https://github.com/izzidevelopers/IzHiddenAI/releases).

## ðŸ–¥ï¸ System Requirements

- **OS:** Windows 10 or newer (64-bit)
- **RAM:** Maximum 1 GB required (runs great on low-memory systems)
- **Processor:** Runs on CPUs less powerful than an Intel Core i3 â€” no high-end hardware needed
- **Disk space:** ~421 MB free space for installation

---

## ðŸ†• What's New in v1.2.0 Beta

- ðŸŽ™ï¸ **Real-time live talk mode** â€” have voice conversations with the AI in real time using WebSocket streaming. It transcribes both sides live and saves full session history.
- ðŸ§° **Live talk tools** â€” during live talks the AI can save/delete/recall memories, search the web, take screenshots, run shell commands, set volume, browse websites, create/read files, and more.
- ðŸ¤– **Agent mode â€” build & download files** â€” ask the AI to create a script, app, HTML page or any file; it opens a terminal sandbox, does the work, and gives you **download buttons** for every file.
- ðŸªŸ **Split-screen mode** â€” use two chat panels side by side (`Ctrl + Shift + S`).
- âš¡ **Quick Run mode** â€” launch the app in a compact input-only window (`Ctrl + Shift + R`).
- ðŸ” **Transparent mode** â€” make the background fully transparent so only the message bubbles float on screen (`Ctrl + Shift + X`).
- ðŸš€ **Run at Windows startup** â€” toggle in Settings to auto-start the app when Windows boots.
- ðŸŒ **Multi-language voice support** â€” auto-detects the language of your text and picks the right TTS voice, or choose your own voice from the picker.
- ðŸ“ **Custom system prompt** â€” add your own instructions in Settings that are included with every chat.
- ðŸ–¼ï¸ **File attachments** â€” drag & drop, paste, or attach files/images for the AI to analyze.
- ðŸŽ¨ **Code syntax highlighting** â€” code blocks in AI responses are color-highlighted by language.
- ðŸ”” **In-app update notifications** â€” the app checks for new versions and alerts you.
- ðŸ“¬ **User feedback system** â€” send feedback directly from the app.

---

## âœ¨ Features

- ðŸ’¬ **Streaming AI chat** â€” instant streaming answers with a visible "thinking" phase
- ðŸŽ™ï¸ **Real-time live talk** â€” voice conversations with live transcription and session history
- ðŸ¤– **Build & download files** â€” the AI uses its terminal sandbox to create scripts, apps or files and gives you **download buttons** for each one
- ðŸŒ **Web search** â€” automatically fetches real-time information from the internet when asked
- ðŸ’» **Run commands** â€” executes local terminal commands on your machine when you ask it to
- ðŸ–¼ï¸ **Images & files** â€” attach screenshots, images, code and documents for the AI to analyze
- ðŸŽ¤ **Voice input** â€” speak your questions; they are transcribed
- ðŸ”Š **Voice replies** â€” auto-reply voice mode reads answers aloud (TTS with multi-language support)
- ðŸ–¥ï¸ **Window & screen capture** â€” snapshot any window, or transcribe its audio (meetings, videos)
- âœ‚ï¸ **Screen crop** â€” crop any part of your screen and send it to the AI
- ðŸ§  **AI memory** â€” remembers important information about you across chats
- ðŸ“š **Chat history** â€” all conversations are saved, searchable, and auto-titled
- ðŸªŸ **Split-screen mode** â€” two chat panels side by side
- âš¡ **Quick Run mode** â€” compact input-only window
- ðŸ” **Transparent mode** â€” floating message bubbles on a transparent background
- âš¡ **Completely hidden from capture** â€” `WDA_EXCLUDEFROMCAPTURE` removes the window from recorders/shares entirely
- âŒ¨ï¸ **Global hotkey** â€” `Ctrl + Shift + Space` hides/shows the app from anywhere
- ðŸš€ **Run at startup** â€” auto-start with Windows

---

## ðŸ› ï¸ Tech Stack

- **Electron 43** â€” desktop shell (frameless, transparent window)
- **React 19 + TypeScript** â€” UI
- **Vite 8** â€” bundler / dev server
- **AharAPI** â€” free keyless OpenAI-compatible API: chat, streaming, tool calling, vision, audio transcription, and the autonomous agent (terminal sandbox + web search + file download links). No API keys are bundled or required.
- **WebSocket streaming** â€” real-time live talk with voice transcription
- **koffi** â€” native FFI used for `SetWindowDisplayAffinity` (`WDA_EXCLUDEFROMCAPTURE`)
- **electron-store** â€” persistent chat threads, memories, settings
- **react-markdown / remark-math / rehype-katex** â€” rich markdown + math rendering
- **framer-motion, lucide-react** â€” animations and icons

---

## ðŸ“¦ How to Install

1. Go to the **[Releases page](https://github.com/izzidevelopers/IzHiddenAI/releases)** of this repository.
2. Download the **`Iz-Hidden-AI-Beta-Setup-1.2.0.exe`** file (~108 MB).
3. Double-click the downloaded installer.
4. Follow the on-screen instructions and wait for the installation to finish (takes about **421 MB** of disk space).
5. Launch **Iz Hidden AI** from your Start Menu or desktop shortcut.
6. The app opens as a hidden window â€” press **`Ctrl + Shift + Space`** to show it.

## âš™ï¸ How It Works

- **Chatting:** Type any question and press `Enter`. The AI streams its answer in real time with a visible "thinking" phase before replying.
- **Live talk:** Click the mic/talk button to start a real-time voice conversation. The AI listens and responds with voice, and both sides are transcribed live. Sessions are saved to your history.
- **Build & download files:** Ask the AI to build something (a script, an HTML page, a small app) and it automatically uses its sandboxed agent terminal, then shows **Download** buttons for the files it creates.
- **Web search:** When a question needs live information, the AI automatically searches the internet and includes the results in its answer.
- **Run commands:** You can ask the AI to run local terminal commands, and it executes them on your machine and shows you the output.
- **Files & images:** Drag & drop, paste, or click the paperclip to attach screenshots, images, code, or documents for the AI to analyze.
- **Voice input:** Click the mic button and speak â€” your words are transcribed.
- **Voice replies:** Toggle the speaker button and the AI will read its answers aloud with TTS. Multi-language support auto-detects your text language.
- **Window & screen capture:** Use the monitor button to pick a window â€” **Audio** transcribes its sound live (meetings, videos), **Snap** takes a screenshot.
- **Screen crop:** Use the scan button to crop any part of your screen and send it as an image.
- **Split-screen:** Press `Ctrl + Shift + S` to open a second chat panel side by side.
- **Quick Run:** Press `Ctrl + Shift + R` to launch in compact input-only mode.
- **Transparent mode:** Press `Ctrl + Shift + X` to make the background transparent â€” only message bubbles float on screen.
- **Memory & history:** The AI saves important facts about you automatically and remembers them across chats. All conversations are saved, searchable, and auto-titled.
- **Run at startup:** Enable in Settings to auto-start the app when Windows boots.
- **Privacy shield:** The window uses `WDA_EXCLUDEFROMCAPTURE` (Windows 10 2004+), so it is **completely invisible** in screen shares, recordings and screenshots â€” not even a black box.

---

## âŒ¨ï¸ Keyboard Shortcuts

| Shortcut | Action |
| --- | --- |
| `Ctrl + Shift + Space` | Hide / show the app window (global) |
| `Ctrl + M` | Toggle **mini mode** â€” shrink the window to a small compact input |
| `Ctrl + Shift + S` | Toggle **split-screen** dual-panel mode |
| `Ctrl + Shift + R` | Toggle **Quick Run** compact input mode |
| `Ctrl + Shift + X` | Toggle **transparent mode** |
| `Ctrl + Shift + A` | Toggle **agent mode** on/off |
| `Ctrl + ,` | Open **Settings** |
| `Ctrl + N` | New chat |
| `Ctrl + F` | Search chat history |
| `Enter` | Send message |
| `Shift + Enter` | New line |

---

## ðŸ’¡ Usage Tips

- Drag & drop or paste files/images into the input box, or click the paperclip to attach.
- Use the scan button to crop any part of your screen and send it as an image.
- The monitor button lets you pick a window: **Audio** transcribes its sound live, **Snap** takes a screenshot.
- The mic button records your voice; toggle the speaker button for spoken replies.
- Try **live talk** mode for real-time voice conversations â€” sessions are saved to your history.
- Ask it to build something â€” a script, an HTML page, a small app â€” and it will automatically use its sandboxed agent terminal, then show **Download** buttons for the files.
- Press **`Ctrl + M`** to shrink the window into a small floating input (mini mode) and again to restore the full chat.
- Press **`Ctrl + Shift + X`** to try transparent mode â€” only the message bubbles are visible.
- Press **`Ctrl + Shift + S`** to open split-screen and use two chats side by side.
- Enable **run at startup** in Settings so the app is always ready when you boot Windows.
- The AI saves important facts to its memory automatically and can be asked to run terminal commands or search the web on demand.

---

## ðŸ—ºï¸ Roadmap

- ðŸªŸ **Windows** â€” available now âœ…
- ðŸ“² **Other platforms** â€” coming soon

---

## ðŸ“„ License

[MIT](LICENSE) Â© 2026 [Izzi Developers](https://github.com/izzidevelopers)
