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

## 📱 Termux (Android) Quick Start

Copy and paste these commands one by one or all at once:

**1. Setup Environment & Clone**
```bash
pkg update && pkg upgrade -y
pkg install nodejs-lts git -y
git clone https://github.com/schoolofengineeringmysore/termux.git
cd termux
```

**2. Install & Run**
```bash
npm install
node bot.js
```

---

## 💻 Desktop (Windows/Mac/Linux) Quick Start

**1. Clone Project**
```bash
git clone https://github.com/schoolofengineeringmysore/termux.git
cd termux
```

**2. Install Dependencies**
```bash
npm install
npx playwright install firefox
```

**3. Run Bot**
```bash
node bot.js
```

---

## 🛠️ Developer Info
- **Developed by**: koushik hy
- **Portfolio**: [koushikhy.netlify.app](https://koushikhy.netlify.app)
