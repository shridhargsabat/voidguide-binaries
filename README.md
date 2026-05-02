# VoidGuide 🌌

VoidGuide is a high-performance, AI-native desktop application designed for seamless codebase exploration and modification. Built with a focus on "Glass" aesthetics and developer velocity, it bridges the gap between raw AI potential and practical filesystem operations.

<p align="center">
  <img src="public/assets/icon.svg" width="128" height="128" alt="VoidGuide Icon">
</p>

## 📥 Downloads

You can download the latest pre-built binaries from the [Releases](https://github.com/shridhargsabat/voidguide-binaries/releases) page.

### Installation Guide

#### 🪟 Windows
1. Download the `.exe` installer from the latest release.
2. Run the installer and follow the on-screen instructions.
3. Launch **VoidGuide** from your Start Menu.

#### 🐧 Linux
VoidGuide provides multiple package formats for Linux:
- **AppImage**: Download the `.AppImage` file, make it executable (`chmod +x`), and run it.
- **Debian/Ubuntu**: Download the `.deb` package and install it using `sudo apt install ./voidguide.deb`.
- **Fedora/RHEL**: Download the `.rpm` package and install it using `sudo dnf install ./voidguide.rpm`.

#### 🍎 macOS
1. Download the `.zip` archive from the latest release.
2. Extract the archive.
3. Drag and drop `VoidGuide.app` into your **Applications** folder.

---

## 🚀 Key Features

- **AI-Native Workflow**: Deep integration with leading AI providers (Google, Anthropic, OpenAI, OpenRouter, Groq, Mistral, DeepSeek, Perplexity, Cohere) for intelligent file reading, searching, and writing.
- **Advanced Model Support**: Full support for **Gemma 4 31B** and Claude 3.5 Sonnet, with native thinking/reasoning extraction.
- **HITL (Human-In-The-Loop) Approval**: Mandatory, high-fidelity approval flow for all filesystem modifications with syntax-highlighted diffs.
- **Visual Agentic Reasoning**: Real-time transparency into the AI's "thought process" via animated reasoning overlays.
- **Zen Startup**: Application launches in a clean, sidebar-less "Zen" mode by default to maximize focus.
- **Glass Aesthetic**: A modern, translucent UI with **34 distinct "Glass" themes** (Dark, Light, Void, Midnight, etc.) and smooth animations.
- **Dynamic Typography**: Theme-aware font pairings (e.g., Poppins, IBM Plex) that adapt instantly when switching themes.
- **High-Performance Search**: Optimized Command Palette (⌘K) with zero-lag interaction.
- **Multi-Session Management**: Robust state persistence with recency-based sorting and automatic session titling.
- **Integrated Terminal**: Native shell access within the app using xterm.js.
- **Smart File Indexing**: Real-time workspace scanning with a highly responsive file tree.
- **Multi-Agent System**: Specialized agents (Coder, Architect, Investigator) with distinct visual tagging.
- **Free Web Research**: Native, 100% free web search capability using a parallel-racing engine (SearXNG + DuckDuckGo).
- **Sophisticated Motion System**: Entirely rebuilt using **Framer Motion**, featuring spring-based physics for all interactions.
- **Keyboard-Centric**: Fast navigation via Command Palette (⌘K), inline chat slash commands (`/`), and file mentions (`@`).

---

## 🛠 Tech Stack

- **Frontend**: [React 19.2](https://react.dev/) + [Vite 8.0](https://vitejs.dev/)
- **Desktop Framework**: [Electron 41.4](https://www.electronjs.org/)
- **Language**: [TypeScript 6.0](https://www.typescriptlang.org/)
- **State Management**: [Zustand](https://zustand-demo.pmnd.rs/) with `electron-store` persistence
- **AI Backend**: Multi-provider support including [Google Gemini](https://ai.google.dev/), [Anthropic Claude](https://www.anthropic.com/), [OpenAI GPT](https://openai.com/), OpenRouter, Groq, Mistral, DeepSeek, Perplexity, and Cohere.
- **Styling & Motion**: [Tailwind CSS v4](https://tailwindcss.com/) for high-performance styling and [Framer Motion](https://www.framer.com/motion/) for spring-based physics.

---

## 🛡 Security & Stability
All binaries are built using a secure CI/CD pipeline. For security and intellectual property reasons, this repository only contains compiled artifacts; the source code is maintained in a private repository.

---
*Built with ❤️ by [Shridhar Sabat](mailto:shridhargsabat@gmail.com) for the next generation of software engineers.*
