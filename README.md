# 🛡️ Montreal MC — Tactical Media Console

> **Military Command // Tactical Viewing Link & Advanced YouTube Stream Deck**

A high-performance, tactical-grade YouTube media console built with a custom dark-mode sci-fi/military aesthetic. Designed for precise stream management, retrograde/prograde time-shifting controls, dynamic resolution requests, and total viewing immersion.

🌐 **Live Deployment & Source Code:** [Montreal MC Tactical Console](https://breaultalex44-cmd.github.io/MMC/)

---

## 📋 Table of Contents

1. [Overview & Features](https://www.google.com/search?q=%23-tactical-features--capabilities)
2. [Technical Stack](https://www.google.com/search?q=%23%EF%B8%8F-technical-stack)
3. [Quick Start / Local Deployment](https://www.google.com/search?q=%23-quick-start--local-deployment)
4. [System Manual & Wiki](https://www.google.com/search?q=%23-system-manual--wiki)

---

## 🎯 Tactical Features & Capabilities

### 📡 1. Target Input & Acquisition

* **Universal URL Parser:** Instantly load videos by pasting full YouTube links, shortlinks (`youtu.be`), live streams, embeds, or raw 11-character video IDs.


* **Visual Scanner Feedback:** Tactical HUD scanning animation on target acquisition.



### ⏱️ 2. Niagara Garrison Command Controls

* **Precision Time-Shift:** Retrograde and prograde jump buttons for rapid retrograde (-5s to -1m) and prograde (+5s to +1m) navigation.


* **Live Telemetry:** Real-time remaining time countdown and calculated Estimated Time of Arrival (ETA) finish clock.


* **Resolution Request Engine:** Request specific stream qualities from 144p up to 2160p 4K UHD, with active stream telemetry reporting.


* **Layout Modes:** Toggle between absolute fullscreen container expansion and customized Theater Mode.


* **Interface Scaling:** Adjust UI scale on the fly (Compact, Standard, Large, Extra Large) to fit any tactical setup.



---

## 🛠️ Technical Stack

| Component | Architecture |
| --- | --- |
| **Frontend** | Vanilla HTML5, Modern ES6+ JavaScript, CSS3

 |
| **Styling** | Custom Dark-Mode Variables, Glassmorphism, Space Grotesk & DM Mono Fonts

 |
| **API Integration** | Official YouTube IFrame Player API

 |

---

## 🚀 Quick Start / Local Deployment

1. Clone or download the repository to your local machine.


2. Open `index.html` in any modern web browser or host it locally.


3. No build steps or complex bundlers required!



```bash
git clone https://github.com/breaultalex44-cmd/MMC.git
cd MMC
# Open index.html directly

```

---

## 📖 System Manual & Wiki

### System Architecture

Montreal MC operates entirely client-side using vanilla web technologies and the official YouTube IFrame Player API. The interface leverages CSS custom properties and high-contrast tactical design elements (`Space Grotesk` and `DM Mono`) to ensure maximum legibility under low-light operating conditions.

### Target Input (Module 01)

The **Surface-to-air unit** input box accepts multiple URL patterns:

* Standard Watch URLs: `[https://www.youtube.com/watch?v=VIDEO_ID](https://www.youtube.com/watch?v=VIDEO_ID)`

* Shortlinks: `[https://youtu.be/VIDEO_ID](https://youtu.be/VIDEO_ID)`

* Embed & Live Paths: `[https://www.youtube.com/embed/VIDEO_ID](https://www.youtube.com/embed/VIDEO_ID)`

* Raw IDs: Exactly 11 alphanumeric characters (`VIDEO_ID`)



Pressing `Enter` or clicking **LOAD VIDEO** initiates target acquisition, triggering the HUD scan animation and loading the asset into the player stage.

### Garrison Controls (Module 02)

The control panel provides advanced management tools:

* **Time Shifting:** Jump forward or backward instantly using the retrograde and prograde matrix.


* **Resolution Requests:** Force quality overrides. Note that YouTube's adaptive streaming algorithm ultimately dictates final delivery depending on client bandwidth and codec availability.


* **Interface Scaling:** Modify UI density via the settings row dropdown to switch between Compact, Standard, Large, and Extra Large viewports.



### Troubleshooting & API Notes

* **Playback Errors:** Error codes (such as embedding restrictions or private video statuses) will trigger an automated tactical toast notification in the top-right corner.


* **Fullscreen Restrictions:** Browser security policies may occasionally require direct browser fullscreen triggers rather than programmatic requests.



---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
