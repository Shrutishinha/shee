

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff416c,50:ff4b2b,100:7c3aed&height=220&section=header&text=SHEE%20%7C%20SURAKSHASAKHI&fontSize=34&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=FF416C&center=true&vCenter=true&width=900&lines=SMART+WOMEN+SAFETY+SYSTEM;REAL-TIME+SOS+EMERGENCY+ALERTS;LIVE+GPS+LOCATION+TRACKING;TECHNOLOGY+FOR+PERSONAL+SAFETY;BUILDING+SAFER+COMMUNITIES" alt="Typing SVG"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-ACTIVE-FF416C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

---

# SHEE — SurakshaSakhi

**SHEE (SurakshaSakhi)** is a web-based women's safety and emergency alert system designed to provide a fast and accessible way to share an SOS alert and live location with trusted contacts during emergency situations.

The application combines **browser geolocation, emergency alerts, responsive UI, and Google Maps integration** to create a simple safety-focused experience.

> **Goal:** Make emergency location sharing faster, simpler, and accessible through a lightweight web application.

---

## ✨ Key Features

| Feature                 | Description                                             |
| ----------------------- | ------------------------------------------------------- |
| 🔴 **One-Tap SOS**      | Quickly activate an emergency alert                     |
| 📍 **Live Location**    | Access the user's current GPS coordinates               |
| 🗺️ **Google Maps**     | Generate a location link from latitude & longitude      |
| 👥 **Trusted Contacts** | Store emergency contacts for quick access               |
| 🔊 **Emergency Alerts** | Audio and visual feedback during SOS activation         |
| 📱 **Responsive UI**    | Designed for desktop and mobile screens                 |
| ⚡ **Lightweight**       | Frontend-focused architecture with minimal dependencies |

---

# 🔄 System Workflow

```text
┌───────────────────────┐
│   Add Trusted Contact │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│      Press SOS        │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│ Request Geolocation   │
│     Permission        │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│ Capture Latitude &    │
│      Longitude        │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│ Generate Google Maps  │
│       Location        │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│ Create Emergency      │
│       Alert           │
└───────────┬───────────┘
            ↓
┌───────────────────────┐
│ Share Alert & Location│
│ With Trusted Contacts │
└───────────────────────┘
```

### How it works

1. The user adds trusted emergency contacts.
2. The user activates the **SOS button** during an emergency.
3. The browser requests access to the device's location.
4. The application retrieves the current latitude and longitude.
5. A Google Maps location link is generated.
6. An emergency message containing the location is prepared.
7. The alert can be shared with the user's trusted contacts.

---

# 🛠️ Technology Stack

| Technology          | Purpose                                               |
| ------------------- | ----------------------------------------------------- |
| **HTML5**           | Page structure and semantic layout                    |
| **CSS3**            | Styling, animations, responsiveness and glassmorphism |
| **JavaScript**      | Application logic and user interactions               |
| **Geolocation API** | Accessing device location                             |
| **Google Maps**     | Location visualization/link generation                |
| **Git & GitHub**    | Version control and project management                |

---

# 📁 Project Structure

```text
A-WEBSITE-FOR-WOMEN-SAFETY/
│
├── index.html
├── style.css
├── script.js
│
├── assets/
│   └── alert.mp3
│
└── README.md
```

---

# 🎯 Project Objectives

* Build a technology-driven personal safety solution.
* Reduce the steps required to trigger an emergency alert.
* Enable quick location sharing with trusted contacts.
* Create a responsive and accessible user interface.
* Explore real-world applications of browser geolocation technology.
* Develop a socially responsible software solution.

---

# 🌐 Use Cases

SHEE can be useful in scenarios such as:

* 🌙 Late-night commuting
* 🎓 College campus safety
* 🚕 Cab or public transport travel
* ✈️ Solo travel
* 🚶 Walking alone
* 🚨 Unexpected emergency situations

---

# 🎨 UI & UX Highlights

* **Glassmorphism-inspired interface**
* **Pulsing SOS button**
* **Animated gradients**
* **Emergency audio feedback**
* **Responsive layout**
* **Clear visual hierarchy**
* **Minimal interaction flow**
* **Mobile-friendly design**

The interface prioritizes **speed and visibility**, especially during emergency interactions.

---

# ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone <YOUR-REPOSITORY-URL>
```

### 2. Open the project

```bash
cd A-WEBSITE-FOR-WOMEN-SAFETY
```

### 3. Run the application

Open:

```text
index.html
```

in a modern web browser.

For the best experience, allow the browser to access your **location** when prompted.

---

# 🔐 Privacy & Safety Considerations

The project uses the browser's **Geolocation API**, which requires user permission before accessing location data.

Important considerations:

* Location access depends on browser permissions.
* GPS accuracy may vary depending on the device and environment.
* Alert delivery depends on network availability.
* The application should not be considered a replacement for official emergency services.
* Production deployment should include secure data handling and authentication.

---

# ⚠️ Current Limitations

* Requires browser location permission.
* Location accuracy depends on the device/GPS.
* Internet connectivity may be required for location sharing.
* Web-based alerts may depend on browser/device capabilities.
* No dedicated backend/database in the current version.
* Not a replacement for official emergency services.

---

# 🚀 Future Roadmap

### Phase 1 — Web Improvements

* [ ] Firebase authentication
* [ ] Cloud-based trusted contacts
* [ ] Improved location tracking
* [ ] Emergency alert history

### Phase 2 — Smart Safety

* [ ] Voice-activated SOS
* [ ] AI-based risk detection
* [ ] Unsafe-area detection
* [ ] Automatic emergency triggers

### Phase 3 — Mobile Application

* [ ] Android application
* [ ] iOS application
* [ ] Background location support
* [ ] SMS-based emergency alerts
* [ ] Emergency contact calling

### Phase 4 — Emergency Integration

* [ ] Police/emergency helpline integration
* [ ] Location sharing with authorized responders
* [ ] Real-time emergency status tracking

---

# 💡 What I Learned

Through this project, I explored:

* Browser **Geolocation API**
* JavaScript event handling
* Responsive web development
* Emergency-focused UI/UX design
* Location-based web functionality
* Client-side application logic
* Designing software for real-world social problems

---

# 📌 Project Highlights

```text
✓ Real-world problem statement
✓ Browse
```
