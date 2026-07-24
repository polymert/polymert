# Hi, I'm Mert a.k.a `@polymert`👋

### Embedded Software Engineer | IoT Developer

I build end-to-end embedded IoT systems — from firmware up through cloud connectivity and the tooling around them. Transitioning deeper into embedded/IoT engineering, with a focus on connected hardware.

---

## 🚀 Currently

- 🔭 Building **Schatzograph** — a full FreeRTOS multi-driver ESP32 firmware project (see below)
- 📡 Deep in Bluetooth Low Energy, ESP32, and MQTT/protobuf pipelines
- 🌱 Currently learning: advanced BLE patterns, CI/CD for embedded systems

---

## 📌 Featured Projects

### 🧭 Schatzograph — ESP32 IoT System

My primary portfolio project: an ESP32-based embedded system built around end-to-end IoT ownership, from hardware bring-up to CI/CD.

- **Firmware:** Full FreeRTOS multi-driver architecture — HTU21, PCF8574, PN532, DS3231, SD card, INA219
- **Connectivity:** MQTT with `nanopb` Protobuf serialization, plus a custom Python decoder
- **Storage & networking:** LittleFS, NVS, FTP server driver, ESPAsyncWebServer with cookie-based session auth
- **Power:** Debugged and resolved a power-chain issue where the MT3608 sagged under ESP32 boot current, moved to a TPS63020 buck-boost converter
- **CI/CD:** Six-stage GitLab pipeline (lint → build → docs → changelog → release → quality-gate) with firmware metadata injection, running on a self-hosted Raspberry Pi 4 runner

### 🔵 BLE Terminal Scanner

A Windows desktop BLE scanner and terminal tool.

- Async BLE scanning built on `bleak`
- Desktop UI with `ttkbootstrap`
- Packaged as a standalone `.exe` via PyInstaller, with a fully automated GitHub Actions build pipeline (dynamic versioning, artifact publishing)

### 🔌 IR Relay Power Switch

A wireless, IR-remote-controlled power switch project.

- ATtiny85 (Digispark) + ESP32 + VS1838B IR receiver driving a bistable relay
- Solved a real-world Windows driver issue (libusb-win32 via Zadig) blocking firmware uploads

---

## 🛠 Tech Stack

### Languages

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**Embedded:** ESP32 · FreeRTOS · Arduino Framework · I²C / SPI / UART · BLE · MQTT · PlatformIO

**Hardware:** KiCad · Power electronics (LiPo, TP4056, buck-boost) · Logic analyzer debugging

**Desktop / Backend:** Python · Bleak · PyInstaller · Tkinter

**Mobile:** React Native · Expo

**Tooling:** Git · GitHub Actions · GitLab CI · Docker · Linux

---

## 📈 GitHub Statistics

![Metrics](./github-metrics.svg)

---

## 📫 Connect

- GitHub: [@polymert](https://github.com/polymert)

---

> _"Per aspera ad astra"_
