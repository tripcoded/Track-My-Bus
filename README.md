# Track My Bus

<div align="center">

**A Smart Bus Monitoring & Real-Time Tracking System**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Active-brightgreen)](https://track-my-bus-teal.vercel.app/)

</div>

Welcome to the **TRACK MY BUS** project! This is a fully functional prototype website designed to showcase real-time bus tracking and monitoring capabilities .

---

## 📋 Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Solution Overview](#solution-overview)
- [Screenshots](#screenshots)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [System Architecture](#system-architecture)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Team](#team)
- [License](#license)

---

## <a id="overview"></a> 📖 Overview

This project demonstrates a smart bus tracking system with real-time monitoring capabilities.

---

## <a id="live-demo"></a> 🔗 Live Demo

Check out the live version of the application here:  
🌐 [Track My Bus Live Demo](https://track-my-bus-teal.vercel.app/)

---

## <a id="screenshots"></a> 📸 Screenshots

![Track My Bus - Amritsar Interface](/screenshot.png)

*Application Interface: Real-time bus tracking with route information and interactive map*

---

## <a id="problem-statement"></a> 🧩 Problem Statement

In many cities and rural areas, public transportation systems face significant challenges:

- ❌ Lack of real-time bus tracking
- ❌ Poor passenger communication
- ❌ Inefficient route monitoring
- ❌ Absence of instant alerts for delays or changes

**Impact:** Passengers often wait without knowing exact arrival times, while authorities lack centralized visibility into bus operations.

---

## <a id="solution-overview"></a> 💡 Solution Overview

This project presents a **Smart Bus Monitoring & Alert System** prototype developed for Smart India Hackathon (SIH).

**Key Capabilities:**

1. **Web-based Interface** – Real-time bus information and route tracking
2. **Data Management** – JSON-based data handling with easy API integration
3. **Visual Tracking** – Interactive map and bus location visualization
4. **Notifications** – Audio alerts for updates and delays
5. **Responsive Design** – Optimized for all devices

The goal is to demonstrate how technology can enhance public transport visibility, improve passenger experience, and streamline operational monitoring using a lightweight, frontend-focused solution.

---

## <a id="key-features"></a> ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🚍 **Bus Information Display** | Structured data for all bus routes and schedules |
| 🔔 **Audio Notifications** | Instant alerts for updates, delays, and arrivals |
| 🖥️ **Interactive UI** | User-friendly, responsive interface |
| 📊 **JSON Data Handling** | Easy to extend and integrate with APIs |
| ⚡ **Lightweight** | Fast performance, browser-based solution |
| 🗺️ **Map Integration** | Visual representation of bus locations and routes |
| 🔧 **Customizable** | Easy to deploy, modify, and extend |

---

## <a id="tech-stack"></a> 🛠 Tech Stack

**Frontend:**
- **HTML5** – Semantic structure and markup
- **CSS3** – Modern styling and responsive design
- **JavaScript (ES6+)** – Dynamic behavior and interactivity

**Data & Tools:**
- **JSON** – Bus data management
- **Git & GitHub** – Version control
- **VS Code** – Development environment

**Deployment:**
- **Vercel** – Live hosting
- **GitHub Pages** – Alternative hosting option

---

## <a id="system-architecture"></a> 🏗 System Architecture

```
┌─────────────────┐
│  User Browser   │
└────────┬────────┘
         │
         ▼
┌─────────────────────────────┐
│   Frontend UI               │
│   (HTML + CSS)              │
└────────┬────────────────────┘
         │
         ▼
┌─────────────────────────────┐
│  JavaScript Logic           │
│  (script.js)                │
└────────┬────────────────────┘
         │
         ▼
┌─────────────────────────────┐
│  Data Layer                 │
│  (bus.json)                 │
└────────┬────────────────────┘
         │
         ▼
┌─────────────────────────────┐
│  Output & Notifications     │
│  (Audio + UI Updates)       │
└─────────────────────────────┘
```

**Future Integration Points:**
- ✅ Live GPS APIs
- ✅ Backend servers (Node.js, Python)
- ✅ Databases (MongoDB, Firebase)
- ✅ Real-time data streaming

---

## <a id="installation--setup"></a> ⚙ Installation & Setup

### Prerequisites

- Any modern web browser (Chrome, Edge, Firefox)
- Git (optional, for cloning)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/tripcoded/Track-My-Bus.git
   ```

2. **Open the application:**
   - **Option A:** Double-click `index.html`
   - **Option B:** Use VS Code Live Server extension (right-click → Open with Live Server)

---

## <a id="usage"></a> ▶ Usage

1. **Launch** the application in any modern web browser
2. **Select** source and destination from dropdown menus
3. **View** real-time bus information and route details
4. **Receive** audio notifications for updates and alerts
5. **Explore** the interactive map for bus locations
6. **Modify** `bus.json` to test with different data

This demo is ideal for presentation, prototyping, and system extension.

---

## <a id="project-structure"></a> 📁 Project Structure

```
track-my-bus/
│
├── index.html           # Main application UI
├── script.js            # Core logic and interactivity
├── bus.json             # Bus data and routes
├── bus.png              # Bus icon asset
├── notify.mp3           # Notification sound
├── README.md            # Project documentation
└── LICENSE              # MIT License
```

---

## <a id="future-enhancements"></a> 🚀 Future Enhancements

| Feature | Priority |
|---------|----------|
| 🔴 Real-time GPS-based tracking | High |
| 📱 Mobile application | High |
| ☁️ Backend integration (Node.js / Firebase) | Medium |
| 📡 Push notifications (SMS / App alerts) | Medium |
| 📈 Admin dashboard for authorities | Medium |
| 🧠 AI-based delay prediction | Low |

---

## <a id="team"></a> 👥 Team

| Role | Name |
|------|------|
| **Project Lead** | Ankit Singh Yadav |
| **Maintainer** | Om Abhishek Tripathi |

### Acknowledgments

Special thanks to the Smart India Hackathon (SIH) initiative for providing the platform to develop innovative solutions for public transportation challenges.

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## <a id="license"></a> 📄 License

This project is licensed under the [MIT License](LICENSE) - feel free to use and modify it!

---

<div align="center">

**Made with ❤️ by the Track My Bus Team**

[⬆ back to top](#track-my-bus--amritsar)

</div>
