<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0d14,50:0057FF,100:F97316&height=170&section=header&text=CyberGenii&fontSize=44&fontColor=ffffff&fontAlignY=40&desc=Software%20%7C%20Mobile%20%7C%20Embedded%20%7C%20IoT&descSize=14&descAlignY=62&descColor=9ca3af&animation=fadeIn" width="100%" alt="CyberGenii"/>

[![Website](https://img.shields.io/badge/Website-0057FF?style=flat-square&logo=googlechrome&logoColor=white)](https://cybergenii.com)
[![Email](https://img.shields.io/badge/Email-F97316?style=flat-square&logo=gmail&logoColor=white)](mailto:cybersgenii@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/message/7FQ35RMU2VVZP1)
[![Dribbble](https://img.shields.io/badge/Dribbble-EA4C89?style=flat-square&logo=dribbble&logoColor=white)](https://dribbble.com/cybergenii)
[![Behance](https://img.shields.io/badge/Behance-1769FF?style=flat-square&logo=behance&logoColor=white)](https://behance.net/cybergenii)

<br/>

**We build scalable software products, developer tools and open-source libraries across web, mobile, embedded systems and IoT.**

*Clean architecture, performance and developer experience are non-negotiable.*

</div>

---

## 🏢 Our Products

- 📦 **[Respatch](https://respatch.com)** · logistics platform for shops, delivery centers, fleet owners and drivers
- ⚡ **[CyberGenii Energy](https://energy.cybergenii.com)** · solar installs, power-as-a-service, solar products and IoT components
- 🎓 **[CyberGenii Academy](https://academy.cybergenii.com)** · Embedded Systems & IoT masterclass program

<!-- Rename Energy and Academy here once the standalone names are chosen -->

---

## 🌟 Flagship Open Source

### ⚡ [Ion](https://github.com/cybergenii/ion) · C++ package manager
![Rust](https://img.shields.io/badge/Rust-F97316?style=flat-square&logo=rust&logoColor=white)
![MIT](https://img.shields.io/badge/MIT-0057FF?style=flat-square)
![Active](https://img.shields.io/badge/Active-10B981?style=flat-square)

> *Cargo-style ergonomics for C++.*

Replaces CMake pain and dependency hell with a clean CLI, TOML manifests and automatic build file generation.

```bash
ion new my-app
ion add fmt spdlog
ion build && ion run
```

**Roadmap:** PubGrub resolution · registry · memory safety linter · LSP

<br/>

### 🐍 [FastAPI SQLAlchemy Starter](https://github.com/cybergenii/fastapi-sqlalchemy-starter) · Backend template
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Active](https://img.shields.io/badge/Active-10B981?style=flat-square)

> *Production-shaped, not toy-shaped.*

FastAPI + async SQLAlchemy with JWT auth, RBAC, Postgres, Redis, Alembic and mail already wired. Clone it, rename it, grow domain modules under `app/core/`.

```bash
uv sync
cp .env.example .env
uvicorn main:app --reload
```

<br/>

### 🔥 [ExpressBolt](https://github.com/cybergenii/expressbolt) · Express + Mongoose layer
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
[![npm](https://img.shields.io/badge/npm-published-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/expressbolt)

> *Stop rewriting the same route handlers.*

One class replaces hundreds of lines of boilerplate: CRUD, pagination, population, field selection, duplicate checks and error handling.

```ts
const crud = new CrudController({ req, res, next });
await crud.getMany<UserI>({
  modelData: { Model: User },
  query: req.query,
});
```

<br/>

### 📊 [Andrea Table](https://github.com/cybergenii/andrea-table) · React data table
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
[![npm](https://img.shields.io/badge/npm-published-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/andrea-table)

> *Every admin dashboard needs a great table.*

Pass one config object, get a production-ready table with API integration, CRUD, sorting, filtering, pagination, custom renderers and theming.

<br/>

### 📱 [Flutter Wireless](https://github.com/cybergenii/flutter_wireless) · Bluetooth package
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
[![pub.dev](https://img.shields.io/badge/pub.dev-published-0057FF?style=flat-square&logo=dart&logoColor=white)](https://pub.dev/packages/flutter_wireless)

> *Bluetooth Serial, done right for Flutter.*

Discovery, connection management, data transfer, auto-pairing, bonding and state monitoring on Android and iOS.

```dart
NewFlutterBluetooth.instance
  .startDiscovery()
  .listen((r) => connectTo(r.device));
```

**Supports:** SPP · BLE · multi-connection · background ops · PIN auto-pair

---

## 📦 More Open Source

- **[mich-pages](https://github.com/cybergenii/mich-pages)** · TS/React · CRUD page generator: define fields once, get full forms ([npm](https://www.npmjs.com/package/mich-pages))
- **[termux-nvim](https://github.com/cybergenii/termux-nvim)** · Shell · one-command Neovim dev environment for Android via Termux

---

## 🛠️ Tech Stack

**Languages**<br/>
[![](https://skillicons.dev/icons?i=ts,js,rust,cpp,python,dart&theme=dark&perline=6)](https://skillicons.dev)

**Frontend & Mobile**<br/>
[![](https://skillicons.dev/icons?i=react,nextjs,flutter,tailwind,vite&theme=dark&perline=6)](https://skillicons.dev)

**Backend**<br/>
[![](https://skillicons.dev/icons?i=nodejs,express,fastapi,django,actix&theme=dark&perline=6)](https://skillicons.dev)

**Data, DevOps & Cloud**<br/>
[![](https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis,docker,aws,gcp,firebase,nginx,linux&theme=dark&perline=10)](https://skillicons.dev)

---

## 🔌 Embedded Systems & IoT

**Boards:** ESP32 · ESP8266 · STM32 · Arduino · Raspberry Pi

**Protocols:** MQTT · BLE · Wi-Fi STA/AP · WebSockets · I2C / SPI / UART · GSM / LTE

**Toolchains:** PlatformIO · ESP-IDF · STM32CubeMX · FreeRTOS · CMake

<details>
<summary><b>📋 Full embedded capabilities (tap to expand)</b></summary>
<br/>

**Firmware & Dev**
- Languages: C · C++ · MicroPython · Embedded Rust
- RTOS: FreeRTOS · Arduino loop model · bare-metal
- OTA: ESP-IDF OTA · Arduino OTA · custom HTTP update server
- Debugging: JTAG · SWD · serial monitor · logic analyzer
- Power: deep sleep · light sleep · wake stubs · battery optimization

**Sensors & Peripherals**
- Environmental: DHT11/22 · BMP280/BME280 · MQ-series gas sensors
- Motion: MPU6050 (IMU) · HC-SR04 (ultrasonic) · PIR
- Display: OLED SSD1306 · TFT ILI9341 · e-Paper · 7-segment
- Connectivity: SIM800L/SIM7600 (GSM/LTE) · NEO-6M (GPS) · nRF24L01 (RF)
- Actuators: servo · stepper · DC motor L298N/L293D · relay modules
- Storage: SD card · EEPROM · LittleFS · SPIFFS

**IoT Architecture**
- Device → Cloud: MQTT (Mosquitto/HiveMQ) → API → database pipeline
- Provisioning: BLE + mobile app pairing · captive portal Wi-Fi setup
- Fleet: remote OTA · telemetry dashboards · alert thresholds
- Edge: TensorFlow Lite Micro inference · local decision logic

</details>

---

<div align="center">

### *Building tomorrow's tools, today.*

[![Website](https://img.shields.io/badge/cybergenii.com-0057FF?style=flat-square&logo=googlechrome&logoColor=white)](https://cybergenii.com)
[![Email](https://img.shields.io/badge/cybersgenii%40gmail.com-F97316?style=flat-square&logo=gmail&logoColor=white)](mailto:cybersgenii@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F97316,50:0057FF,100:0a0d14&height=90&section=footer" width="100%" alt=""/>

</div>
