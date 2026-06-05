# Repository Audit & Refactoring Recommendations

This audit reviews your 14 public repositories, assessing their technical complexity, classifying them into performance tiers, and recommending professional renames and descriptions. Adding descriptive write-ups is critical: **empty description fields are a major red flag for recruiters**, who often skip repositories without context.

---

## 🚀 Flagship Tier (Pin & Highlight)

These projects demonstrate advanced systems architecture, hardware-software integration, full-stack complexity, and hackathon execution. They should be pinned.

### 1. `wall_view`
- **Recommended Name**: `RuView-WiFi-Sensing`
- **Recommended Description**: "An advanced, edge-AI WiFi sensing platform leveraging ESP32 Channel State Information (CSI) and Spiking Neural Networks (SNN) for camera-free human pose estimation, breathing rate, and heartbeat tracking."
- **Stack**: Rust, C++, Node.js, WebAssembly
- **Why**: Incredible technical depth. Shows systems programming (Rust/C++), edge AI (SNNs), and deep signal processing.

### 2. `SafeSpeak_GDG_hackathon`
- **Recommended Name**: `SafeSpeak-Community-Safety`
- **Recommended Description**: "An anonymous, location-aware public safety reporting platform built for the GDG Hackathon. Enables citizens to securely report incidents, and authorities to monitor, triage, and resolve alerts via a dynamic React dashboard."
- **Stack**: React 19, Node.js, Express, MongoDB, Framer Motion, Tailwind CSS
- **Why**: Shows full-stack web development maturity, modern frontend design (Framer Motion, React 19), database schemas, and hackathon execution.

### 3. `offline_whatsapp`
- **Recommended Name**: `MeshChat-Offline-Messenger`
- **Recommended Description**: "A real-time, peer-to-peer messaging application designed to run completely offline over a local WiFi mesh network. Creates a self-contained local communication network without internet, cloud, or SIM cards."
- **Stack**: HTML, Node.js, Express, Socket.io
- **Why**: Shows creative networking skills, WebSockets, offline-first design patterns, and Node.js backend architecture.

### 4. `HACKZION.V3__Event-Horizon`
- **Recommended Name**: `Smart-Irrigation-IoT`
- **Recommended Description**: "A full-stack cyber-physical Smart Plant Monitoring & Irrigation system built for HackZion Hackathon. Deploys ESP8266 NodeMCU microcontrollers with capacitive soil moisture sensors and DHT22 to stream real-time telemetry to a web dashboard."
- **Stack**: JavaScript, C++ (ESP8266/Arduino), Node.js, CSS
- **Why**: Shows physical computing, IoT hardware engineering, and dynamic web telemetry.

### 5. `BMSCE-Weather-Prediction`
- **Recommended Name**: `NASA-TimeSeries-Weather-Prediction`
- **Recommended Description**: "An intelligent meteorological forecasting platform that leverages 5 years of historical NASA satellite data to predict local temperature, rainfall, wind speed, and humidity up to 6 months in advance using Time Series Analysis."
- **Stack**: HTML, Python, Flask, Time-Series Models
- **Why**: Showcases data science, working with large public API data (NASA), and time-series mathematics.

---

## 📈 Mid-Tier (Support & Showcase)

These projects display solid utility, specific domain knowledge (AI, ML, hardware hacking), or neat client-side engineering.

### 6. `study-focus`
- **Recommended Name**: `FocusGuard-AI-Monitor`
- **Recommended Description**: "An AI-powered gaze and blink monitoring application built using Python and Google MediaPipe Face Landmarker. Tracks focus levels, eye blink rates, and distraction states in real-time."
- **Stack**: Python, MediaPipe, OpenCV
- **Why**: Excellent showcase of Computer Vision, real-time edge AI, and user experience telemetry.

### 7. `WOW`
- **Recommended Name**: `WOWW-AI-Weather-Forecaster`
- **Recommended Description**: "Intelligent AI-powered weather forecasting and rainfall prediction web application. Uses Machine Learning models (Python/Flask) to analyze atmospheric parameters and output localized weather forecasts."
- **Stack**: Python, Flask, HTML, CSS, Scikit-learn
- **Why**: Showcases Python backend (Flask) integrated with Scikit-learn machine learning.

### 8. `0.1_jammer` & `2.0_jammerr` *(Recommend merging into one repository)*
- **Recommended Name**: `ESP32-NRF24-Signal-Blocker`
- **Recommended Description**: "A low-level hardware prototyping codebase using ESP32 and NRF24L01 transceivers to research RF signal disruption, frequency channel scanning, and packet transmission in the 2.4GHz spectrum."
- **Stack**: C++ (Arduino/ESP32)
- **Why**: Demonstrates low-level hardware knowledge, register-level understanding of NRF24L01 transceivers, and SPI bus communication.

### 9. `morse-code-generator` & `morse-code-generator_2.0` *(Recommend merging or keeping 2.0)*
- **Recommended Name**: `Morse-Code-Chrome-Extension`
- **Recommended Description**: "A lightweight Google Chrome Extension that converts text to Morse code audio patterns and visual flashes in real-time. Built using vanilla browser APIs and extension manifest v3."
- **Stack**: JavaScript, HTML, CSS, Chrome Extension API
- **Why**: Demonstrates browser API integration, utility script architecture, and UX styling.

---

## 🗄️ Educational & Archives (Clean up / Hide from Pinning)

These are older frontend exercises, hackathon scratchpads, or forks. Keep them public but do not highlight them.

### 10. `FashionBoutique`
- **Recommended Name**: `Fashion-Boutique-Landing`
- **Recommended Description**: "A responsive and modern frontend landing page for a fashion boutique showcasing seasonal clothing lines. Built with clean semantic HTML5 and vanilla CSS."
- **Stack**: HTML, CSS

### 11. `the-crucibles`
- **Recommended Name**: `NASA-SpaceApps-Crucibles`
- **Recommended Description**: "A front-end visualization portal designed during the NASA Space Apps Challenge to present planetary science concepts."
- **Stack**: HTML, CSS

### 12. `nit-patna` (Forked from InfoNaveen/nit-patna)
- **Recommended Name**: `nit-patna-face-attendance`
- **Recommended Description**: "A customized fork of the NIT Patna attendance portal, incorporating OpenCV face-verification and blink detection algorithms to prevent photographic spoofing."
- **Stack**: Python, OpenCV, JavaScript
