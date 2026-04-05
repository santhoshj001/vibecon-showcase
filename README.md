# VibeCon Showcase Projects

A collection of projects demonstrating product thinking, infrastructure design, and practical solutions to real problems.

---

## 🏗️ Nodrithm Dev Simulator

**Full-stack IoT device simulator for building automation**

Built to validate the Nodrithm Labs energy monitoring platform without waiting for real hardware. This simulator handles complete building automation workflows including MQTT messaging, device state management, and Home Assistant integration.

**What it does:**
- Simulates IoT devices for campus energy monitoring
- Full building automation testing environment
- Production-grade infrastructure for startup validation

**Tech:** Python, React, Docker, MQTT, Home Assistant

**Repository:** [nodrithm-dev-simulator](https://github.com/santhoshj001/nodrithm-dev-simulator)

---

## 🎤 VoiceKeyboard

**Android app with persistent floating bubble for speech-to-text transcription**

A production-ready Android app that provides system-wide voice input capability. The floating bubble interface makes voice transcription accessible from any app on the device, eliminating the need to switch contexts.

**What it does:**
- Persistent floating bubble accessible across all apps
- Real-time speech-to-text powered by Moonshine STT engine
- Automatic clipboard integration for seamless text pasting
- Optional accessibility service for direct text injection
- Smart auto-collapse after silence timeout

**Key Features:**
- Works system-wide, not just within the app
- On-device transcription (no cloud dependency)
- Clean MVVM architecture with 4 modules
- Built for Android 15+ with modern Jetpack Compose UI

**Tech:** Kotlin, Jetpack Compose, Moonshine STT, Koin DI, MVVM Clean Architecture

**Repository:** [voicekeyboard](https://github.com/santhoshj001/voicekeyboard)

---

## 📖 VoiceRead

**Self-hosted PDF-to-audiobook app with natural AI voices**

A local-first alternative to Speechify that transforms any PDF into an audiobook with natural Indian English voices. Built for accessibility and privacy, everything stays on your machine with no cloud uploads or tracking.

**What it does:**
- Upload any PDF and listen to it like an audiobook
- Real-time sentence highlighting with auto-scroll
- Choose from ~40 natural voices powered by Sarvam AI
- Pause, resume, and pick up exactly where you left off
- Smart incremental audio generation for instant playback
- Local caching eliminates redundant API calls

**Key Features:**
- **Privacy-first:** All documents and audio cached locally
- **Document library:** Upload, organize, search, and manage PDFs
- **Smart playback:** Audio generated in chunks, first sentence plays within seconds
- **Speed control:** 0.75x to 2x playback speeds
- **Self-hosted:** Free alternative to subscription services
- **Docker-ready:** Deploy with one command

**Tech:** Next.js 16, React 19, Fastify 5, SQLite, Drizzle ORM, Sarvam AI TTS, Docker

**Repository:** [VoiceRead](https://github.com/santhoshj001/VoiceRead)

---

**Contact:** [santhoshj296@gmail.com](mailto:santhoshj296@gmail.com)  
**LinkedIn:** [linkedin.com/in/santhoshj001](https://www.linkedin.com/in/santhoshj001)  
**GitHub:** [github.com/santhoshj001](https://github.com/santhoshj001)
