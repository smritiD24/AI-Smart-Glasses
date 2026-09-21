# DivyaDrishti — AI Smart Glasses for the Visually Impaired

**AidenAI, Bangalore | June 2026 – Present**

> ⚠️ This is a proprietary project developed at AidenAI, Bangalore. Source code is confidential and not included in this repository. This repository documents the system architecture, hardware assembly, and feature set.

---

## Overview

DivyaDrishti is a deployable AI-powered smart glasses system designed to assist visually impaired users through real-time perception, multilingual voice interaction, and wearable edge computing. The system integrates multiple AI capabilities into a single lightweight wearable device, operable entirely through voice commands.

---

## Features

| Feature | Description |
|---|---|
| 👤 Face Recognition | Identifies known individuals and announces their name via voice |
| 🌍 Scene Description | Describes the surrounding environment in natural language |
| 💵 Currency Reading | Detects and reads currency notes aloud |
| 🗺️ Landmark & Navigation | Identifies landmarks and provides navigation assistance |
| 👗 Apparel Detection | Describes clothing and colours to the user |
| 🦺 Safety Detection | Alerts user to potential hazards in the environment |
| 🎙️ Multilingual Voice Commands | Full voice-based interaction in multiple languages |

---

## System Architecture

```
┌─────────────────────────────────────────────────────┐
│                   WEARABLE DEVICE                   │
│                                                     │
│   Camera Module → Raspberry Pi Zero 2 W            │
│                 → Python AI Backend                 │
│                 → UPS + Battery Pack                │
│                 → LED Indicators                    │
└─────────────────────┬───────────────────────────────┘
                      │ Bluetooth / WiFi
┌─────────────────────▼───────────────────────────────┐
│                 ANDROID APPLICATION                  │
│                                                     │
│   Voice Command Input → Processing → Voice Output  │
│   User Interaction  →  Feature Trigger             │
└─────────────────────────────────────────────────────┘
```

---

## Hardware

See [HARDWARE.md](HARDWARE.md) for full component list, wiring, and assembly details.

**Core components:**
- Raspberry Pi Zero 2 W (edge compute)
- Camera module
- UPS (uninterruptible power supply)
- Li-ion battery pack
- LED indicators
- Custom wearable assembly (glasses frame)

---

## Tech Stack

| Layer | Technology |
|---|---|
| Hardware | Raspberry Pi Zero 2 W, Camera, UPS, Battery, LEDs |
| Backend | Python, Linux |
| Mobile App | Android Studio (Java/Kotlin) |
| Frontend/Integration | JavaScript |
| AI/ML | Computer Vision, NLP, Voice Processing |
| Interface | Multilingual voice commands |

---

## My Contributions

- Independently assembled the complete wearable hardware from components including Raspberry Pi Zero 2 W, camera module, UPS, battery pack, and LEDs
- Developed the Python/Linux backend for perception, AI inference, and system control
- Built the Android application for user interaction and voice command processing
- Integrated all hardware and software components into a single deployable wearable system
- Implemented multilingual voice command interface for accessibility

---

## Hardware Photos

<p align="center">
  <img src="assets/hardware_front.jpg" width="400" alt="DivyaDrishti — Front View"/>
  <img src="assets/hardware_side.jpg" width="400" alt="DivyaDrishti — Side View"/>
</p>

> Hardware assembled independently at AidenAI, Bangalore.

---

## Status

- [x] Hardware assembly complete
- [x] Python/Linux backend developed
- [x] Android application developed
- [x] Feature integration complete (face recognition, scene description, currency, navigation, apparel, safety)
- [x] Multilingual voice interface implemented
- [ ] Deployment ongoing

---

## Organisation

**AidenAI, Bangalore**
AI solutions for accessibility and assistive technology.

---

## Author

**Smriti Dandin**
AI/ML Engineer Intern — AidenAI, Bangalore
MSc Student, IIT Gandhinagar

[Your email] | [Your LinkedIn]
