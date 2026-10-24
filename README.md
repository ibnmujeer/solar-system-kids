# 🪐 Interactive 3D Solar System & Earth Globe Explorer

> **100% Offline. Zero Dependencies. Single-File HTML.**  
> Built for teachers, classrooms, parents, and curious space explorers of all ages. No internet connection, web server, or installation required.

---

## 🚀 Two Complete Standalone Editions Included

Both editions pack the entire **Three.js 3D WebGL engine**, **procedural planetary textures**, **scientific fact databases**, and **177 interactive country boundaries** into a single `.html` file (~930 KB) that you can share via USB drive, email, WhatsApp, or school LMS and open on any device with a double-click or tap.

| Feature | 🎓 `solar-system-standalone.html` (Main Classroom Edition) | 🎈 `solar-system-kids-standalone.html` (Kids Edition, Ages 5+) |
| :--- | :--- | :--- |
| **Target Audience** | Middle/high school students, teachers, and general learners | Young explorers aged **5 and above** (and early readers) |
| **Scientific Facts** | Detailed planetary profiles, AU distances, orbital periods, and diameter ratios verified against **NASA NSSDCA** & **IAU** | Playful nicknames, fun comparisons (e.g., floating Saturn in a giant bathtub), and stories verified against **NASA Space Place** |
| **Read-Aloud Voice** | Text-based classroom reference panels | **Built-in Offline Voice Narrator** (`Web Speech API` with Indian English `en-IN` voice priority) that reads every planet and country aloud! |
| **3D Earth Map** | Natural Earth 1:110m Cultural Vectors (177 countries) | **Official Survey of India Composite Boundary** (full J&K, Ladakh, and Arunachal Pradesh unified) + **"Find India!"** one-tap zoom button |
| **Device Optimization** | Desktop, laptop, interactive smartboards, and mobile browsers | **Mobile-First Portrait & Landscape**, tablet, and desktop with expanded 3D touch hit-spheres for small fingers |

---

## ✨ Key Highlights

### 1. 🌌 Interactive 3D Solar System
* **The Sun + All 8 Major Planets:** Mercury, Venus, Earth (with its orbiting Moon), Mars, Jupiter (with its Great Red Spot), Saturn (with its bright ring system and Cassini Division), Uranus (tilted on its side at 97.77 degrees with its faint ring), and Neptune.
* **Offline Procedural Canvas Textures:** Every planet surface, cloud band, crater, and ring is painted dynamically on HTML5 2D canvases at startup, meaning zero external image files can ever fail to load offline.
* **Smooth Camera Tracking:** Tap or click any planet (or pick it from the bottom quick-select bar) to fly smoothly toward it, lock the camera onto its orbit, and open its discovery card.
* **Classroom Orbit Controls:** Pause or resume planetary orbits at any time, orbit the camera 360 degrees, zoom in/out, or reset to the full Solar System overview.

### 2. 🌍 Rotatable 3D Earth Globe & Country Identification
* **Seamless Transition to Earth:** Click **"Visit Earth Globe"** in the top bar (or inside Earth's discovery panel) to transition from outer space to a high-resolution, rotatable 3D globe of Earth.
* **Tap Any Country to Highlight & Identify:** Clicking or tapping any country on the 3D globe runs a real-time 3D spherical raycast and 2D point-in-polygon check, lighting up the country's 3D borders in glowing gold and displaying its name, continent, and region.
* **Official Map of India (Kids Edition):** Specifically engineered for Indian students and classrooms, `solar-system-kids-standalone.html` uses the **Official Survey of India / DataMeet Composite Boundary** for India (including the complete Union Territories of Jammu & Kashmir and Ladakh, plus Arunachal Pradesh) rendered cleanly on top with zero conflicting internal lines, and opens the Earth Globe facing India first.

### 3. 🔊 Read-Aloud Voice Narration (Kids Edition)
* **Automatic Offline Speech:** When a child taps a planet, the Sun, or a country on the globe in `solar-system-kids-standalone.html`, the planet introduces itself in the first person (*"Zoom, zoom! I am Mercury, the closest planet to the Sun..."*).
* **Kid-Paced & Clear:** Automatically selects Indian English (`en-IN`) voices when available on the device, tuned to a warm, clear storytelling pace (`rate: 0.93`, `pitch: 1.06`).
* **Full Audio Controls:** Includes a big golden **"Read to Me!"** / **"Hear Again"** replay button and a top **"Voice: ON / OFF"** mute toggle for quiet classroom time.

### 4. 📱 True Mobile Phone, Tablet & Smartboard Support
* **Full-Screen `100dvh` WebGL Viewport:** Engineered to fill 100% of portrait and landscape mobile phone screens without browser address-bar squishing.
* **Portrait-Aware 3D Camera:** Automatically scales camera distance and elevation on narrow portrait phone screens so all 8 planetary orbits fit inside the screen width and selected planets sit centered above the compact bottom card.
* **Forgiving Touch Targets:** Invisible expanded 3D hit-spheres around smaller rocky planets and a `10px` finger-tap tolerance make tapping moving planets effortless for 5-year-olds on phones and tablets.

---

## 🎮 Controls Guide

| Action | Mouse (Desktop / Laptop) | Touch (Phone / Tablet / Smartboard) |
| :--- | :--- | :--- |
| **Orbit Camera / Spin Globe** | Left-Click + Drag | 1-Finger Drag |
| **Zoom In / Out** | Scroll Wheel | 2-Finger Pinch |
| **Pan Camera (Solar System)** | Right-Click + Drag | 2-Finger Drag |
| **Select a Planet or the Sun** | Click the planet in 3D or click its pill in the bottom bar | Tap the planet in 3D or tap its pill in the bottom bar |
| **Identify a Country on Earth** | Click any landmass on the 3D Earth Globe | Tap any landmass on the 3D Earth Globe |

---

## ⚡ Quick Start (Offline Usage)

No Node.js, Python, or local web server is needed to run either file:

1. **For Young Children (Ages 5+, Phones, Tablets, Home & Primary School):**
   * Double-click or tap **`solar-system-kids-standalone.html`** to open it in Chrome, Safari, Edge, or Firefox.
2. **For Older Students & Classroom Projection:**
   * Double-click or tap **`solar-system-standalone.html`** to open it in any modern browser.
3. **Sharing Offline:**
   * Because each `.html` file is 100% self-contained, you can copy either file onto a USB flash drive, AirDrop it to iPads, or send it over WhatsApp/email and open it directly without an internet connection.

---

## 📚 Verified Scientific Sources & Data Licenses

Every planetary measurement and factual claim in both editions is verified against reputable astronomical authorities:

* **NASA NSSDCA Planetary Fact Sheet (Metric & Ratio to Earth Values):**  
  Compiled by Dr. David R. Williams, NASA Goddard Space Flight Center (`https://nssdc.gsfc.nasa.gov/planetary/factsheet/`).
* **NASA Space Place (Kids Edition Science Portal):**  
  Official NASA educational facts for children (`https://spaceplace.nasa.gov/planets/en/`).
* **NASA Science Solar System Exploration:**  
  Planetary overview and satellite counts (`https://science.nasa.gov/solar-system/planets/`).
* **International Astronomical Union (IAU):**  
  Resolution B5 (2006) definition of the eight major planets and Working Group for Planetary System Nomenclature (WGPSN).
* **Geographic Country Boundaries & Licenses:**
  * **Global Country Polygons:** Natural Earth 1:110m Cultural Vectors, Admin 0 Countries v5.1.1 (`https://www.naturalearthdata.com/`), licensed under **Public Domain (CC0 1.0 Universal)**.
  * **Official India Composite Boundary (Kids Edition):** Survey of India / DataMeet Composite Country Boundary (`https://github.com/datameet/maps`), licensed under **Creative Commons Attribution (CC-BY) / Open Data**.

---

## 🧪 Running the Automated Test Suites (For Developers)

If you have the full project repository, automated unit and integration tests verify planet data integrity, NASA diameter ratios, 3D raycast picking math, voice narrator selection, and point-in-polygon country identification (including full boundary checks for India across New Delhi, Srinagar, Gilgit-Baltistan, Leh, Aksai Chin, Tawang, and Bengaluru):

* **In Any Browser (Offline, No CLI Needed):**
  * Open `tests/test-runner.html` (Main Edition)
  * Open `kids-edition/tests/test-runner.html` (Kids Edition)
* **Via Node.js CLI:**
  ```bash
  node tests/solarSystem.test.js
  node kids-edition/tests/kidsSolarSystem.test.js
  ```
