# Persian PWA 🇮🇷

A modern **Progressive Web App** for learning Persian (Farsi) — with lessons, flashcards, spaced repetition, speech features, and full offline support.

## ✨ Features

- **Interactive Lessons** & **Flashcards**
- **Spaced Repetition System (SRS)** for better retention
- **Speech-to-Text (STT)** and **Text-to-Speech (TTS)**
- **Progress Tracking** with visual bars and statistics
- **Offline-first** – Works without internet (thanks to Service Worker)
- **Installable PWA** – Feels like a native app on mobile/desktop
- **RTL + Persian-first** design
- Responsive & beautiful UI

## 🚀 Tech Stack

- **React** + JSX/TSX
- **Vite** (build tool)
- **PWA**: Service Worker (`sw.js`), Web App Manifest
- **State Management**: Custom hooks (`useProgress`, `useSRS`, etc.)
- **Speech APIs**: Web Speech API (STT/TTS)
- **Storage**: Local storage utilities
- Tailwind CSS or custom styling (with RTL support)

## 📱 Quick Start

1. Clone the repo:
   ```bash
   git clone https://github.com/veritasndiema-ctrl/persian-pwa.git
   cd persian-pwa
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

5. **Install as PWA**: Open in Chrome/Edge → Click install icon in address bar.

## 📖 Usage

- Browse curriculum → Start lessons
- Practice with flashcards (spaced repetition)
- Use voice input/output for pronunciation
- Track your daily progress

## 📁 Project Structure

```
persian-pwa/
├── public/
│   └── manifest.json
├── src/
│   ├── components/     # ExerciseCard, NavBar, HeartBar, etc.
│   ├── pages/          # Home, Lesson, Flashcards, Progress
│   ├── data/           # lessons.json, curriculum.json
│   ├── hooks/          # useProgress, useSRS, useSTT, useTTS
│   ├── utils/          # storage, sm2 (SuperMemo algorithm)
│   ├── sw.js           # Service Worker (PWA)
│   └── main.jsx
├── vite.config.js
└── README.md
```

## 🛠️ Development

- Add new lessons in `src/data/lessons.json`
- Customize curriculum in `curriculum.json`
- Improve STT/TTS in the respective hooks

## 📄 License

MIT License — see [LICENSE](LICENSE) file.

## 👤 Author

**Keith Ndiema K**  
[veritasndiema-ctrl](https://github.com/veritasndiema-ctrl)
