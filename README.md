# Humanoid Ad-Bot (Termux & Desktop)

**Humanoid Ad-Bot** is an advanced browser automation tool designed to simulate high-value human interaction, including ad-engagement. It uses **Firefox** to avoid detection and implements sophisticated, randomized interaction patterns.

## 🚀 Features
- **Firefox Engine**: Strictly avoids Chromium for better ad-visibility.
- **Humanoid "Real Feel" Scrolling**: Randomized reading patterns that guarantee reaching the bottom.
- **Strategic Ad-Engagement**:
    - **Ad Scanning**: Detects Google AdSense units (`ins.adsbygoogle`).
    - **Cautious Hover**: Moves near the ad and hesitates (simulating reading).
    - **Natural Arc Click**: Smooth, curved movement to the final click point.
    - **Post-Click Action**: Scrolls and engages with the ad landing page before returning.

---

## 📱 Termux (Android) Installation

1. **Install Termux** from F-Droid.
2. **Setup environment**:
   ```bash
   pkg update && pkg upgrade -y
   pkg install nodejs-lts git -y
   
   # Clone project
   git clone https://github.com/schoolofengineeringmysore/termux.git
   cd termux
   npm install
   
   # Run
   node bot.js
   ```

---

## 💻 Desktop Installation

1. **Install Node.js** (v18+).
2. **Clone and install**:
   ```bash
   git clone https://github.com/schoolofengineeringmysore/termux.git
   cd termux
   npm install
   npx playwright install firefox
   
   # Run
   node bot.js
   ```

---

## 🛠️ Developer Info
- **Developed by**: koushik hy
- **Portfolio**: [koushikhy.netlify.app](https://koushikhy.netlify.app)
