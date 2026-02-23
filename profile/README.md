<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0d14,50:0057FF,100:F97316&height=200&section=header&text=CyberGenii&fontSize=70&fontColor=ffffff&fontAlignY=38&desc=Software%20%7C%20Mobile%20%7C%20Embedded%20%7C%20IoT&descSize=18&descAlignY=58&descColor=9ca3af&animation=fadeIn" width="100%"/>

[![Website](https://img.shields.io/badge/cybergenii.com-0057FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://cybergenii.com)
[![Email](https://img.shields.io/badge/Email-F97316?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cybersgenii@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/message/7FQ35RMU2VVZP1)
[![Dribbble](https://img.shields.io/badge/Dribbble-EA4C89?style=for-the-badge&logo=dribbble&logoColor=white)](https://dribbble.com/cybergenii)
[![Behance](https://img.shields.io/badge/Behance-1769FF?style=for-the-badge&logo=behance&logoColor=white)](https://behance.net/cybergenii)

<br/>

> **We build scalable software products, developer tools, and open-source libraries**
> **across web, mobile, embedded systems, and IoT engineering.**
>
> *From production-grade backends to Flutter apps, npm packages, and firmware —*
> *clean architecture, performance, and developer experience are non-negotiable.*

</div>

---

## 🌟 Flagship Projects

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Ion — C++ Package Manager
[![Rust](https://img.shields.io/badge/Built%20with-Rust-F97316?style=flat-square&logo=rust&logoColor=white)](https://github.com/cybergenii/ion)
[![License](https://img.shields.io/badge/License-MIT-0057FF?style=flat-square)](https://github.com/cybergenii/ion)
[![Status](https://img.shields.io/badge/Status-Active-10B981?style=flat-square)]()

> *Bringing Cargo-style ergonomics to the C++ ecosystem*

Replaces painful CMake configuration and C++ dependency hell with a clean CLI, TOML manifests, and automatic build file generation.

```bash
ion new my-app       # scaffold a C++ project
ion add fmt spdlog   # add dependencies  
ion build && ion run # build and run
```

**Roadmap:** Dependency resolution via PubGrub · Package registry · Built-in memory safety linter · LSP integration

[![View Repo](https://img.shields.io/badge/→%20View%20Repo-0a0d14?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cybergenii/ion)

</td>
<td width="50%" valign="top">

### 🔥 ExpressBolt — Express + Mongoose Layer
[![TypeScript](https://img.shields.io/badge/Built%20with-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/cybergenii/expressbolt)
[![npm](https://img.shields.io/badge/npm-published-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/expressbolt)
[![Status](https://img.shields.io/badge/Status-Active-10B981?style=flat-square)]()

> *Stop writing the same route handlers over and over*

One class replaces hundreds of lines of boilerplate — CRUD, pagination, population, field selection, duplicate checks, error handling.

```typescript
const crud = new CrudController({ req, res, next });
await crud.getMany<UserI>({
  modelData: { Model: User, select: ["-password"] },
  query: req.query, // ?page=1&sort=-createdAt
});
```

[![View Repo](https://img.shields.io/badge/→%20View%20Repo-0a0d14?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cybergenii/expressbolt)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Andrea Table — React Data Table
[![TypeScript](https://img.shields.io/badge/Built%20with-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/cybergenii/andrea-table)
[![npm](https://img.shields.io/badge/npm-published-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/andrea-table)
[![Status](https://img.shields.io/badge/Status-Active-10B981?style=flat-square)]()

> *Every admin dashboard needs a great table. Here's ours.*

Config-driven React data table — pass one object, get a production-ready table with API integration, CRUD, sorting, filtering, pagination, custom renderers, and theming.

```tsx
<NewTable data={{
  baseUrl: "https://api.example.com",
  subUrl: "/users",
  heading: [...],
  fn: { fetchFn },
  crud: { add: true, edit: true, delete: true }
}} />
```

[![View Repo](https://img.shields.io/badge/→%20View%20Repo-0a0d14?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cybergenii/andrea-table)

</td>
<td width="50%" valign="top">

### 📱 Flutter Wireless — Bluetooth Package
[![Dart](https://img.shields.io/badge/Built%20with-Dart-0175C2?style=flat-square&logo=dart&logoColor=white)](https://github.com/cybergenii/flutter_wireless)
[![pub.dev](https://img.shields.io/badge/pub.dev-published-0057FF?style=flat-square&logo=dart&logoColor=white)](https://pub.dev/packages/flutter_wireless)
[![Status](https://img.shields.io/badge/Status-Active-10B981?style=flat-square)]()

> *Bluetooth Serial, done right for Flutter*

Handles device discovery, connection management, data transfer, auto-pairing, bonding, and Bluetooth state monitoring across Android and iOS.

```dart
NewFlutterBluetooth.instance
  .startDiscovery()
  .listen((result) => connectTo(result.device));
```

**Supports:** SPP · BLE · Multi-connection · Background ops · PIN auto-pair

[![View Repo](https://img.shields.io/badge/→%20View%20Repo-0a0d14?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cybergenii/flutter_wireless)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

### Languages
[![My Skills](https://skillicons.dev/icons?i=ts,js,rust,cpp,python,dart&theme=dark)](https://skillicons.dev)

### Frontend & Mobile
[![My Skills](https://skillicons.dev/icons?i=react,nextjs,flutter,tailwind,scss,vite&theme=dark)](https://skillicons.dev)

### Backend & Systems
[![My Skills](https://skillicons.dev/icons?i=nodejs,express,fastapi,django,actix&theme=dark)](https://skillicons.dev)

### Databases & DevOps
[![My Skills](https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis,docker,github&theme=dark)](https://skillicons.dev)

### Cloud & Infrastructure
[![My Skills](https://skillicons.dev/icons?i=aws,gcp,firebase,nginx,linux&theme=dark)](https://skillicons.dev)

</div>

---

### 🔌 Embedded Systems & IoT

<div align="center">

| 🔲 Microcontrollers | 📡 Protocols | 🔧 Toolchains |
|:---:|:---:|:---:|
| ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white) | ![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white) ![BLE](https://img.shields.io/badge/Bluetooth%20LE-0082FC?style=flat-square&logo=bluetooth&logoColor=white) | ![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white) |
| ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) | ![WiFi](https://img.shields.io/badge/Wi--Fi%20STA%2FAP-0057FF?style=flat-square&logo=wifi&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white) | ![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white) ![CubeMX](https://img.shields.io/badge/STM32CubeMX-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) |
| ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white) | ![I2C](https://img.shields.io/badge/I2C%20%2F%20SPI%20%2F%20UART-555555?style=flat-square) ![GSM](https://img.shields.io/badge/GSM%20%2F%20LTE-F97316?style=flat-square) | ![FreeRTOS](https://img.shields.io/badge/FreeRTOS-003153?style=flat-square) ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white) |

</div>

<details>
<summary><b>📋 Full Embedded Capabilities</b></summary>
<br/>

**Firmware & Dev**
- Languages: C · C++ · MicroPython · Embedded Rust
- RTOS: FreeRTOS · Arduino loop model · bare-metal
- OTA Updates: ESP-IDF OTA · Arduino OTA · custom HTTP update server
- Debugging: JTAG · SWD · Serial monitor · logic analyzer
- Power: Deep sleep · light sleep · wake stubs · battery optimization

**Sensors & Peripherals**
- Environmental: DHT11/22 · BMP280/BME280 · MQ-series gas sensors
- Motion: MPU6050 (IMU) · HC-SR04 (ultrasonic) · PIR
- Display: OLED SSD1306 · TFT ILI9341 · e-Paper · 7-segment
- Connectivity: SIM800L/SIM7600 (GSM/LTE) · NEO-6M (GPS) · nRF24L01 (RF)
- Actuators: Servo · stepper · DC motor L298N/L293D · relay modules
- Storage: SD card · EEPROM · LittleFS · SPIFFS

**IoT Architecture**
- Device → Cloud: MQTT (Mosquitto/HiveMQ) → API → database pipeline
- Provisioning: BLE + mobile app pairing · captive portal Wi-Fi setup
- Fleet: Remote OTA · telemetry dashboards · alert thresholds
- Edge: TensorFlow Lite Micro inference · local decision logic

</details>

---

## 📦 All Open Source Projects

<div align="center">

| Project | Stack | Description | Links |
|---|---|---|---|
| **ion** | ![Rust](https://img.shields.io/badge/-Rust-F97316?style=flat-square&logo=rust&logoColor=white) | C++ package manager — TOML manifests, CMake generation, Cargo-style CLI | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/ion) |
| **expressbolt** | ![TS](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Express](https://img.shields.io/badge/-Express-000?style=flat-square&logo=express) | CRUD middleware for Express + Mongoose — pagination, population, error handling | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/expressbolt) [![npm](https://img.shields.io/badge/-npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/expressbolt) |
| **andrea-table** | ![TS](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) | Config-driven React data table — API fetching, sorting, filtering, CRUD | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/andrea-table) [![npm](https://img.shields.io/badge/-npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/andrea-table) |
| **mich-pages** | ![TS](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) | CRUD page generator — define fields once, get full Create/Update/View forms | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/mich-pages) [![npm](https://img.shields.io/badge/-npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/mich-pages) |
| **flutter_wireless** | ![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) | Bluetooth Serial — discovery, connection, data transfer, auto-pairing | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/flutter_wireless) [![pub](https://img.shields.io/badge/-pub.dev-0175C2?style=flat-square&logo=dart&logoColor=white)](https://pub.dev/packages/flutter_wireless) |
| **repoflow** | ![TS](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | CLI + web UI for GitHub repo automation — commits, backdating, multi-account | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/repoflow) [![npm](https://img.shields.io/badge/-npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/repoflow) |
| **termux-nvim** | ![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) | One-command Neovim + full dev environment for Android via Termux | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/termux-nvim) |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F97316,50:0057FF,100:0a0d14&height=120&section=footer&fontSize=14&fontColor=ffffff&animation=fadeIn" width="100%"/>

**Building tomorrow's tools, today.**

[![Website](https://img.shields.io/badge/cybergenii.com-0057FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://cybergenii.com)
[![Email](https://img.shields.io/badge/cybersgenii%40gmail.com-F97316?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cybersgenii@gmail.com)

</div>
