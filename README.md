# 📡 TONIX – WiFi Radar

> An educational Wi-Fi signal analysis and visualization app for cybersecurity students and network learning.

## ⚠️ Educational & Authorized Use

TONIX is designed for Wi-Fi education, network administration, and authorized testing.

- Scan and analyze networks only where you have permission.
- The app does not crack passwords or bypass network security.
- Signal-based distance and direction are estimates only.
- Respect privacy and local laws.

---

## ✨ Features

### 🔍 Wi-Fi Network Scanner
Scan nearby Wi-Fi networks and view:

- SSID / hidden network status
- Security type
- Signal strength in dBm
- Wi-Fi channel
- Frequency

### 📡 Radar Visualization
A radar-style display shows nearby networks and their relative signal strength.

### 🔐 Network Details
View available network information such as:

- SSID
- BSSID
- Security
- Signal strength
- Channel
- Frequency

### 📶 Signal Strength Meter
Signal quality is displayed in dBm.

- 🟢 Strong: approximately -30 to -60 dBm
- 🟡 Medium: approximately -61 to -75 dBm
- 🔴 Weak: approximately -76 to -90 dBm

### 📏 Estimated Signal Range
Displays an approximate range based on signal readings.

> Wi-Fi signal strength alone cannot determine an exact distance or exact access-point location.

### 🗺️ Real-Time Signal Survey Map
While the user moves through an authorized survey area, TONIX can record signal readings and visualize them on a map.

Features:

- Live signal readings
- Signal history
- Stronger-signal areas
- Educational signal heatmap
- Best observed signal zone

### 📍 Target Signal Mode
The user can select an authorized Wi-Fi network as a target.

The app monitors:

- Current dBm reading
- Signal improving or decreasing
- Previous readings
- Strongest observed survey area

### 🧭 Live Signal Detector Mode
A metal-detector-style mode provides automatic feedback based on the changing signal strength of an authorized Wi-Fi network.

#### 🔊 Dynamic Audio Feedback
- Weak signal → slower, spaced feedback
- Improving signal → feedback becomes more frequent
- Strong signal → rapid feedback

#### 📳 Haptic Feedback
Optional vibration can also change with signal strength:

- Weak → slow pulses
- Medium → faster pulses
- Strong → rapid pulses

This allows the user to observe signal changes without continuously looking at the screen.

> This mode indicates changing signal strength and stronger observed areas. It does not guarantee the exact physical location of a router or device.

### 📈 Signal History
Track how the signal changes over time with:

- dBm history
- Timestamped readings
- Signal trend visualization

### ⚡ Speed Meter
For a connected and authorized Wi-Fi network, the app can provide connection measurements such as:

- Download speed
- Upload speed
- Latency
- Connection status

---

## 📱 Main Screens

1. Wi-Fi Radar Home
2. Network Details
3. Signal Strength Meter
4. Real-Time Signal Survey Map
5. Target Signal Mode
6. Live Signal Detector Mode
7. Speed Meter

---

## 🎓 Learning Goals

TONIX helps students learn about:

- Wi-Fi fundamentals
- SSID and BSSID
- Wireless security concepts
- Wi-Fi channels and frequencies
- RSSI and dBm
- Signal propagation
- Wireless site surveys
- Android Wi-Fi APIs

---

## 🛠️ Suggested Technology Stack

- Kotlin
- Android SDK
- Jetpack Compose or XML
- Android Wi-Fi APIs
- Location APIs where required
- Mapping SDK for optional survey visualization

### Suggested Architecture

```text
UI
 ↓
ViewModel / State Management
 ↓
Wi-Fi Scanner + Signal Analyzer
 ↓
Android Wi-Fi APIs
```

---

## 📂 Suggested Project Structure

```text
tonix-wifi-radar/
├── app/
│   └── src/main/
│       ├── ui/
│       ├── scanner/
│       ├── signal/
│       ├── detector/
│       ├── survey/
│       ├── models/
│       └── viewmodel/
├── screenshots/
├── README.md
└── LICENSE
```

---

## 🛡️ Responsible Use

TONIX is an educational wireless analysis tool. Use it only on networks and in locations where you have permission to perform scanning or signal surveys.

**Learn. Analyze. Secure.**
