# Selfory ✍️🧠  
*Personalized Language Learning with AI + Hardware Integration*

Selfory is an AI-powered mobile app and hardware project designed to seamlessly blend your real-life experiences with language learning. Whether you're reading a book, scanning a note, or tapping on-screen text, Selfory makes vocabulary acquisition contextual, memorable, and truly yours.

---

## 🌟 Features

### 🧠 Smart Sentence Generation
- Translates selected text and uses AI to generate **example sentences based on your life** or personal data (journal entries, chats, notes, etc.).
- Supports **custom knowledge bases** for tailored sentence generation.

### 📱 Floating Translation Assistant
- Tap on any text on your phone → instantly get translation, pronunciation, and AI-generated sentences in a floating widget.

### 🖋️ Screenless Translation Pen (Hardware Integration)
- A compact **screenless translation pen** scans printed text and sends it to the Selfory app via **Bluetooth**.
- The app instantly translates and returns contextual results to your device.

---

## ⚙️ Tech Stack

### Platforms
- Android (minimum SDK 26+)
- Future support for iOS

### Programming Languages
- Kotlin (Android App)
- C/C++ or Embedded C (Pen Firmware)
- Python (AI Backend, Sentence Generation)

### Core Tools
- Jetpack Compose (UI)
- Bluetooth Low Energy (BLE) integration
- OpenAI / LLM APIs for sentence generation
- SQLite / Room (local DB for user data and personal context)

---

## 🔐 Privacy and Security
- All personal data used for sentence generation is **processed locally or via secure encrypted channels**.
- Users can **choose and edit** the personal sources they wish to include (e.g., journals, chat exports).

---

## 🧩 Compatibility

| Component          | Compatibility Details                  |
|-------------------|-----------------------------------------|
| Android App        | Android 8.0+                           |
| Translation Pen    | BLE-compatible, cross-platform capable |
| AI Backend         | Cloud-hosted or optional local server  |

---

## 🔭 Future Roadmap
- iOS version
- Offline LLM support
- Real-time listening translation mode
- Study history tracking and spaced repetition system

---

## 📂 Project Directory Structure

```bash
selfory/
├── app/                   # Android source code
├── hardware/              # Firmware and circuit design (ESP32, etc.)
├── backend/               # AI sentence generator
├── assets/                # Logos, icons, mockups
├── docs/                  # Documentation and specs
└── README.md
