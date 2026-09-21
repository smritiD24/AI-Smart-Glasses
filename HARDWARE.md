[Hardware.pdf](https://github.com/user-attachments/files/32462429/Hardware.pdf)# Hardware — DivyaDrishti Smart Glasses

## Component List

| Component | Purpose |
|---|---|
| Raspberry Pi Zero 2 W | Edge compute — runs all AI inference and backend logic |
| Camera Module | Visual input — captures real-time frames for AI processing |
| UPS Module | Uninterruptible power supply — prevents data loss on power fluctuation |
| Li-ion Battery Pack | Portable power source for untethered wearable use |
| LED Indicators | System status feedback (power on, processing, error states) |
| Glasses Frame | Wearable form factor — houses all components |

---

## Assembly

All hardware was independently assembled, including:

- Mounting Raspberry Pi Zero 2 W within the glasses form factor
- Positioning and securing the camera module for forward-facing capture
- Integrating UPS and battery for continuous portable operation
- Routing power and data connections within the wearable enclosure
- Placing LED indicators for user-visible system status

---

## System Flow

```
Camera captures frame
        ↓
Raspberry Pi Zero 2 W receives frame
        ↓
Python backend runs AI inference
        ↓
Result sent to Android app via Bluetooth/WiFi
        ↓
Android app converts result to voice output
        ↓
User hears response through speaker/earphone
```

---

## Notes

- Device is designed to be fully self-contained and wearable
- All processing runs on-device (edge inference) via Raspberry Pi Zero 2 W
- UPS ensures clean shutdown and prevents SD card corruption during field use


## Hardware Photos



---
