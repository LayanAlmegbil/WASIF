# 🤟 Wasif: AI-Powered Arabic Sign Language Translator

**Wasif** is a bi-directional communication system that bridges the gap between the Deaf/Mute community and the hearing world through real-time Arabic Sign Language recognition and generation using Artificial Intelligence.

---

## Project Objective

To enable accessible and inclusive communication by:
- Translating **sign language into Arabic speech** using computer vision and deep learning.
- Converting **spoken Arabic into sign language** gestures performed by a 3D avatar.

---

## Key Features

- 🔄 Bi-directional communication: Sign ↔ Speech
- 🧠 Real-time AI processing
- 🇸🇦 Fully supports Arabic language (text, voice, and sign)
- 🛠️ Offline functionality for accessibility
- 👤 3D avatar with automatic hand animation (MediaPipe + Unity)
- 📱 Mobile-optimized for high-performance devices

---

## System Overview

### 1. Sign-to-Speech (Real-Time)
- Detects hand landmarks using **MediaPipe**
- Classifies the gesture using a trained **Keras deep learning model**
- Converts the recognized sign to **Arabic text and speech** using `gTTS`

### 2. Speech-to-Sign
- Transcribes spoken Arabic using a **speech-to-text (STT)** model
- Maps the recognized text to **sign language gestures**
- Animates a 3D avatar (ReadyPlayerMe / Mixamo) using **Unity + landmark-based motion**
