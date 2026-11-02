# Auction Market Theory (AMT) Master Academy
*Interactive Web Application & Progressive Web App (PWA)*

A complete, responsive, institutional educational platform based on **Auction Market Theory**, **Market Profile**, and **Dalton Auction Mechanics**.

---

## 📱 Features

- **9 Master Modules:** Complete curriculum covering continuous auctions, the $Price + Time = Value$ equation, profile anatomy, the 4 profile archetypes (D, P, b, B), Dalton day types, core trade setups, participant psychology, and order flow alignment.
- **Interactive Tools:**
  - **The 80% Rule Calculator:** Dynamic entry, stop, Target 1 (POC), and Target 2 (VAL/VAH) calculator with real-time risk/reward ratios.
  - **Dalton Opening Diagnostic Engine:** Step-by-step interactive decision engine to diagnose RTH opening types (*Open-Drive*, *Open-Test-Drive*, *Open-Rejection-Reverse*, *Open-Auction*) and actionable bias.
  - **Profile Archetypes Explorer:** Interactive SVG diagrams displaying HVN, LVN, POC, single prints, and institutional trade tactics for D-shape, P-shape, b-shape, and B-shape profiles.
- **Interactive Mastery Drills:** Case-study scenarios with instant scoring, feedback, and institutional explanations.
- **Progress Tracking:** Automatically saves completed lessons and quiz responses in browser `localStorage`.
- **Mobile First & PWA Ready:** Installable on iOS (Safari) and Android (Chrome) as an offline app with its own home screen icon.

---

## 🚀 Quick Start (Desktop)

Simply double-click `index.html` to open it immediately in any web browser (Chrome, Edge, Safari, Firefox). Zero installation or npm build required.

---

## 📲 How to Test on Mobile via Local Wi-Fi

To preview the app on your mobile phone right now over your local Wi-Fi:

1. Open PowerShell in this folder:
   ```powershell
   cd C:\Users\Antho\.gemini\antigravity\scratch\amt-academy
   ```
2. Start a simple local server using Python:
   ```powershell
   python -m http.server 8080
   ```
3. Find your computer's local IP address (`ipconfig`, look for IPv4, e.g. `192.168.1.50`).
4. On your phone's browser (Safari or Chrome), navigate to:
   ```
   http://<YOUR-IP>:8080
   ```

---

## 🌐 How to Share Online for Free (Permanent Shareable URL)

### Option 1: GitHub Pages (Recommended — 100% Free)
1. Create a new repository on [GitHub](https://github.com) named `amt-academy`.
2. Push or upload the files (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `README.md`) to the repository.
3. In the repository settings, go to **Settings** &rarr; **Pages**.
4. Under **Branch**, select `main` (or `master`) and folder `/ (root)`, then click **Save**.
5. Within 60 seconds, GitHub will give you a live shareable URL:
   ```
   https://<your-username>.github.io/amt-academy/
   ```
   Anyone on mobile or desktop can access this link anywhere in the world!

### Option 2: Vercel / Netlify (Drag & Drop)
1. Go to [vercel.com](https://vercel.com) or [netlify.com](https://netlify.com).
2. Drag and drop the `amt-academy` folder onto the dashboard.
3. Instant live HTTPS URL is generated with global CDN delivery.

---

## 📲 Installing as an App on Mobile Phones

Once hosted or opened via URL:
- **iPhone / iPad (Safari):**
  1. Open the URL in Safari.
  2. Tap the **Share** button (box with an arrow pointing up).
  3. Scroll down and tap **"Add to Home Screen"**.
  4. Tap **Add**. The app icon will appear on your phone's home screen and open in full-screen standalone mode.
- **Android (Chrome):**
  1. Open the URL in Chrome.
  2. Tap the **three vertical dots** in the top-right corner.
  3. Tap **"Install App"** or **"Add to Home screen"**.
