# 🛡️ Raksha Kavach — The Stealth & Speak Web-App

> **"Designed for Complete Safety, Built for Absolute Accessibility."**
> Raksha Kavach is a revolutionary, zero-barrier, stealth-first Progressive Web App (PWA) designed to provide instant protection to women, especially those with limited technical knowledge or literacy.

---

## 🌟 Why Raksha Kavach is Unique (The Hackathon USP)
Most women's safety apps fail in real-world scenarios because they force users to download massive apps, register accounts, remember passwords, or navigate complex, text-heavy screens. 

**Raksha Kavach bypasses all of this:**
*   **Zero Download Friction:** Built as a **Progressive Web App (PWA)**. Just scan a QR code, and the app is ready on any phone in under 2 seconds.
*   **Zero Login Barrier:** No logins, signups, or databases. User data (emergency contacts and photos) is saved completely securely and privately inside the browser's **Local Storage**.
*   **Empathy-Driven Design:** Built using the **"Professional Polish"** UI layout, keeping the most critical interactions completely touch-friendly, visual, and highly accessible.

---

## 🚀 Key Features

### 1. 🎭 Chameleon Mode (Stealth Security)
*   **The Mask:** Upon launch, the app behaves as a highly convincing, elegant Indian recipe blog titled *"Swaad & Swasthya"* featuring beautiful photos of popular dishes (e.g., Paneer Butter Masala).
*   **The Trigger:** If the user **rapidly triple-taps** (3 clicks within 1 second) on the main recipe image, the blog instantly transitions into the dark, high-contrast **Emergency Dashboard** in under 100 milliseconds.
*   **Stealth Advantage:** Attackers will never suspect the app is a safety tool even if they snatch the victim's phone.

### 2. 🗣️ Zero-Text UI & Voice-Activated SOS
*   **Large Visual Contacts:** Designed specifically for low-literacy users. Emergency contact cards show large, high-quality family photographs (Papa, Bhai, Police) instead of relying on written text.
*   **Voice Trigger (Web Speech API):** A pulsing microphone button listens for local, urgent trigger words like **"Help"**, **"Bachao"**, **"Save Me"**, or **"Police"** in both Hindi and English. Once triggered, the alert sequence is automatically initiated.
*   **Audio Guidance (Web Speech Synthesis):** Long-pressing or hovering on any card reads the action out loud in clear Hindi (e.g., *"Papa ko phone lagane ke liye yahan dabayein"*), ensuring no technical knowledge is required.

### 3. 🗺️ Local Angels Network (Safe Havens)
*   Instead of pointing to a distant police station 5 km away, the app maps registered nearby safe spots (Kirana shops, medical stores, active auto stands) within a 500-meter radius.
*   An elegant, interactive radar-styled mockup (rendered on HTML5 Canvas) shows the user's live position (pulsing blue dot) and allows them to navigate to a physical safe-haven instantly.

### 4. ⚡ Offline-First & SMS Fallback
*   If the user has an active internet connection, GPS coordinates are simulated to transmit securely.
*   **No Internet Fallback:** If the network is lost, the app automatically falls back to native cellular services, preparing an SMS body pre-filled with the active emergency numbers and the user's last known location: 
    *   *Formula: sms://[Phone_Number]?body=HELP! I am in danger. My location: https://maps.google.com/?q=[Latitude],[Longitude]*

---

## 🛠️ Technology Stack
*   **Frontend:** Plain HTML5, Semantic CSS3, Vanilla JavaScript (ES6+).
*   **APIs Used:** 
    *   Web Speech API (`SpeechRecognition`) for hands-free voice triggers.
    *   Web Speech Synthesis API (`speechSynthesis`) for real-time Hindi audio guidance.
    *   HTML5 Canvas API for rendering the dynamic Safe Havens Map.
    *   Web Storage API (`localStorage`) for offline photo and contact saving using Base64 strings.

---

## 💻 Setup & Installation (Local Execution)
Since this is a lightweight, pure web app, it requires absolutely no heavy IDE setups or server configurations:

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/raksha-kavach.git
    ```
2.  Navigate to the directory and double-click `index.html` to run it in any modern browser (Chrome, Safari, Edge).
3.  To test PWA features: Host the folder on a local server (like Live Server extension in VS Code) or deploy it for free on GitHub Pages/Vercel.

---

## 🎨 UI Layout Design ("Professional Polish" Template)
The app's Emergency Dashboard is engineered based on modern visual ergonomics:
*   **Left-Side Anchor:** A massive, glowing SOS button occupies the left column, designed to fall perfectly inside a thumb's natural reach.
*   **Top-Right Panel:** A wide, landscape-style map showing the Local Angels Network, ensuring maps are readable at a quick glance.
*   **Bottom Grid:** Symmetrically placed, large horizontal contact cards featuring photos/custom avatars for instant tactile feedback.

---

## 🏆 Hackathon Pitch Framework (How to Win Judges Over)
When presenting this project on stage, highlight these 3 pillars:
1.  **We design for the 90%:** *"Most safety apps are designed by elite developers for tech-savvy city women. Raksha Kavach is built for EVERY woman, regardless of her literacy level or technology exposure."*
2.  **No Server, No Leaks:** *"Because we store all sensitive user data locally on the user's phone, we protect users' privacy and locations from server leaks, maintaining absolute zero-compromise security."*
3.  **The Stealth Factor:** *"The best safety feature is the one that stays invisible. Chameleon Mode ensures that even in an active threat situation, a victim can summon help without raising an attacker's suspicion."*

---
*Created with care by Yuvraj Patidar — Built to protect, designed to empower.*
