# NeuroPlay: Gaming with Brainwaves
*A beginner-friendly brain–computer interface (BCI) project for Build.*

Control a simple endless-runner game using **focus**, **relaxation**, and **blinks** from an EEG headband. This project runs for **9 weeks** and is designed for beginners to learn hardware, software, and HCI—together.

## ✨ MVP (9 weeks)
- Focus → speed up
- Relax → slow down
- Blink → jump
- Calibration screen + basic smoothing (EMA + blink debounce )

## 🧱 Stack
- **Firmware:** Arduino (Bluetooth/Serial bridge)
- **App:** Python + Pygame (or Unity as a variant)
- **ML/UX:** simple filters (EMA, thresholds), per-user calibration
- **Collab:** GitHub Issues • Projects • Discussions

## 🚀 Quick Start

> Start with the **simulator** so the app works before hardware is ready.

```bash
# 1) Run the simulator (emits JSON with attention/meditation/blink)
python simulator/simulate_stream.py | python teams/app/main.py

