# CyberGenii

We build scalable software products, developer tools, and open-source libraries
across web, mobile, embedded systems, and IoT engineering.

From production-grade backends to Flutter apps, npm packages, and firmware —
our work focuses on clean architecture, performance, and developer experience.

---

## 🌟 Flagship Projects

### ⚡ Ion — C++ Package Manager
> *Bringing Cargo-style ergonomics to the C++ ecosystem*

A modern C++ package manager and project scaffolding tool written in **Rust**.
Ion replaces the painful ritual of manual CMake configuration and dependency
management with a clean CLI, TOML-based manifests, and automatic build file
generation — the way C++ tooling should have always worked.

- `ion new my-app` — scaffold a production-ready C++ project in seconds
- `ion.toml` — simple, readable dependency manifest (inspired by Cargo.toml)
- Auto-generates `CMakeLists.txt` — no more hand-written CMake
- Built-in linter and memory safety checks *(in development)*
- Dependency resolution via PubGrub algorithm *(in development)*
- Cross-platform: Linux · macOS · Windows

**Stack:** Rust · TOML · CMake · PubGrub
→ [github.com/cybergenii/ion](https://github.com/cybergenii/ion)

---

### 🔥 ExpressBolt — Express.js + Mongoose CRUD Layer
> *Stop writing the same route handlers over and over*

A TypeScript npm package that wraps Express.js and Mongoose with a clean
`CrudController` API. One class handles create, read, update, delete — with
built-in filtering, sorting, pagination, nested population, field selection,
duplicate checking, and environment-aware error responses.

- `new CrudController({ req, res, next })` → `.getMany()`, `.create()`, `.update()`, `.delete()`
- `generateDynamicSchema<T>()` — generate Mongoose models from TypeScript interfaces
- Query string support: `?page=1&limit=10&sort=-createdAt&fields=name,email`
- Multi-level population: nested `path` + `second_layer_populate`
- Global `errorCenter()` middleware with dev/production stack trace toggle

**Stack:** TypeScript · Express.js · Mongoose · MongoDB
→ [github.com/cybergenii/expressbolt](https://github.com/cybergenii/expressbolt)

---

### 📊 Andrea Table — React Data Table Component
> *Every admin dashboard needs a great table. Here's ours.*

A fully config-driven React data table component published on npm. Pass a
single configuration object and get a production-ready table with API
integration, multi-column sorting, advanced filtering, pagination, CRUD
actions, custom cell renderers, color theming, and auto-refresh — zero
boilerplate.

- Remote API fetching with a single `fetchFn` callback
- Custom column renderers via `ColumnT<T>[]` — render anything per cell
- Built-in export, row selection, search, and visibility toggles
- Color theming via `color` prop — fits any design system
- Auto-refresh with configurable interval
- Full TypeScript generics — `TableDataT<YourModel>`

**Stack:** TypeScript · React · Tailwind CSS · Vite
→ [github.com/cybergenii/andrea-table](https://github.com/cybergenii/andrea-table)

---

## 🛠️ Tech Stack

### **Languages**
| Domain | Languages |
|---|---|
| Web & Backend | TypeScript · JavaScript (ES6+) |
| Systems & Firmware | Rust · C · C++ |
| Scripting & Data | Python |
| Mobile | Dart |

---

### **Frontend**
- **Frameworks:** React.js · Next.js
- **Styling:** Tailwind CSS · SCSS · Styled Components · CSS3
- **Build Tools:** Vite · Webpack · Rollup
- **State Management:** Zustand · Redux · React Query

---

### **Mobile**
- **Cross-Platform:** Flutter · React Native
- **Native Android:** Java · Kotlin (basic)
- **Dart Packages:** pub.dev publishing · platform channels · BLE/Bluetooth integration
- **Device Features:** Camera · GPS · Bluetooth Serial · File System · Push Notifications

---

### **Backend**
- **Node.js:** Express.js · Fastify · NestJS
- **Rust:** Axum · Actix-web
- **Python:** FastAPI · Django · Flask
- **APIs:** RESTful · GraphQL · WebSockets · WebRTC
- **Authentication:** JWT · OAuth2 · Passport.js · API Keys · 2FA
- **Task Queues:** BullMQ · Celery
- **Caching:** Redis · In-memory

---

### **Databases & ORMs**
| Type | Technologies |
|---|---|
| Relational | PostgreSQL · MySQL · SQLite |
| NoSQL | MongoDB · Firebase Firestore · Redis |
| ORMs | SeaORM · TypeORM · Mongoose · SQLAlchemy · Sequelize · Prisma |
| Migrations | SeaORM Migrate · Alembic · Knex |

---

### **Embedded Systems & IoT**

#### Microcontrollers & Platforms
| Platform | Details |
|---|---|
| **ESP32 / ESP32-S3** | Wi-Fi + BLE SoC · dual-core · FreeRTOS · deep sleep · OTA updates |
| **ESP8266** | Wi-Fi SoC · low-power IoT nodes · AT commands |
| **Arduino (AVR/ARM)** | ATmega328 · ATmega2560 · Arduino Nano/Uno/Mega |
| **STM32** | ARM Cortex-M · HAL/LL drivers · CubeMX |
| **Raspberry Pi** | Linux SBC · GPIO · I2C · SPI · UART · Python/C++ |

#### Communication Protocols
| Protocol | Use Case |
|---|---|
| **MQTT** | Lightweight pub/sub for IoT telemetry |
| **HTTP / HTTPS** | RESTful device-to-cloud communication |
| **WebSockets** | Real-time bidirectional device data streams |
| **Bluetooth Serial (SPP)** | Device pairing and data transfer |
| **BLE (Bluetooth Low Energy)** | Low-power sensor beaconing and mobile integration |
| **Wi-Fi (STA/AP/STA+AP)** | Network provisioning and cloud connectivity |
| **I2C / SPI / UART** | Sensor and peripheral bus communication |
| **OneWire** | Temperature sensor chains (DS18B20 etc.) |
| **PWM / ADC / DAC** | Motor control, analog sensing, audio output |

#### Firmware & Embedded Dev
- **Languages:** C · C++ · MicroPython · Embedded Rust
- **RTOS:** FreeRTOS · Arduino loop model · bare-metal
- **Toolchains:** PlatformIO · Arduino IDE · ESP-IDF · STM32CubeIDE
- **OTA Updates:** ESP-IDF OTA · Arduino OTA · custom HTTP update server
- **Debugging:** JTAG · SWD · Serial monitor · logic analyzer
- **Power Management:** Deep sleep · light sleep · wake stubs · battery optimization

#### Sensors & Peripherals
- **Environmental:** DHT11/22 (temp/humidity) · BMP280/BME280 (pressure/altitude) · MQ-series (gas)
- **Motion:** MPU6050 (IMU) · HC-SR04 (ultrasonic) · PIR motion sensors
- **Display:** OLED (SSD1306/SH1106) · TFT LCD (ILI9341) · e-Paper · 7-segment
- **Connectivity:** SIM800L/SIM7600 (GSM/LTE) · NEO-6M (GPS) · nRF24L01 (RF)
- **Actuators:** Servo · stepper motor · DC motor (L298N/L293D) · relay modules
- **Storage:** SD card (SPI) · EEPROM · LittleFS · SPIFFS

#### IoT Architecture
- **Device → Cloud:** MQTT broker (Mosquitto/HiveMQ) → backend API → database
- **Device Provisioning:** BLE + mobile app pairing · captive portal Wi-Fi setup
- **Fleet Management:** Remote OTA · device telemetry dashboards · alert thresholds
- **Edge Computing:** On-device ML inference (TensorFlow Lite Micro) · local decision logic

---

### **DevOps & Infrastructure**
- **CI/CD:** GitHub Actions · self-hosted runners
- **Containers:** Docker · Docker Compose
- **Cloud:** AWS (EC2, S3, Lambda) · GCP · Firebase · DigitalOcean
- **Reverse Proxy:** Nginx · Caddy
- **Monitoring:** Uptime checks · log aggregation · error tracking

---

### **Developer Tooling**
- **Editors:** Neovim · VS Code · Android Studio
- **Version Control:** Git · GitHub · conventional commits
- **Mobile Dev on Android:** Termux + Neovim environment
- **Package Publishing:** npm · pub.dev · crates.io
- **API Testing:** Postman · curl · custom test harnesses
- **Build Systems:** Cargo · CMake · Make · Gradle

---

## 📦 Open Source

| Project | Stack | Description |
|---|---|---|
| [ion](https://github.com/cybergenii/ion) | Rust | C++ package manager — TOML manifests, CMake generation, Cargo-style CLI |
| [expressbolt](https://github.com/cybergenii/expressbolt) | TypeScript · Express · Mongoose | CRUD middleware — pagination, population, error handling |
| [andrea-table](https://github.com/cybergenii/andrea-table) | TypeScript · React | Config-driven data table with API fetching, sorting, filtering |
| [mich-pages](https://github.com/cybergenii/mich-pages) | TypeScript · React | CRUD page generator — define fields once, get full forms |
| [flutter_wireless](https://github.com/cybergenii/flutter_wireless) | Dart · Flutter · Java | Bluetooth Serial — discovery, connection, data transfer |
| [repoflow](https://github.com/cybergenii/repoflow) | TypeScript · Python · Shell | CLI + web UI for GitHub repo automation |
| [termux-nvim](https://github.com/cybergenii/termux-nvim) | Shell | Neovim + dev environment setup for Android via Termux |

---

## 🌐 Links

🌍 [cybergenii.com](https://cybergenii.com)
📧 [hello@cybergenii.com](mailto:hello@cybergenii.com)
💬 [WhatsApp](https://wa.me/message/7FQ35RMU2VVZP1)
🎨 [Dribbble](https://dribbble.com/cybergenii) · [Behance](https://behance.net/cybergenii)
