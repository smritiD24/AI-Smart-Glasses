

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

<img width="1600" height="1200" alt="5" src="https://github.com/user-attachments/assets/ff04eaba-92af-469b-9ec0-f4c63ef7afb2" />
<img width="1600" height="1200" alt="4" src="https://github.com/user-attachments/assets/ad853b6d-c9d4-4d10-bb45-36481ab38956" />
<img width="1600" height="1200" alt="3" src="https://github.com/user-attachments/assets/d2c2bc5b-8ead-4c86-ba2e-dc61e40e3b11" />
<img width="1600" height="1200" alt="2" src="https://github.com/user-attachments/assets/1ba146aa-77d3-45ef-b2d5-d28e6eb52493" />
<img width="1200" height="1600" alt="1" src="https://github.com/user-attachments/assets/b7372934-4001-481a-b331-502f85a61264" />


---
