# MADEL SCORE by JPS 🎾

A high-performance, professional-grade Padel and Tennis scorekeeper designed for zero-latency operation during active play. This web-based application is optimized to work seamlessly across mobile, desktop, and smart display environments.
Named after the author's Padel group **Madel - Minggu Padel** that plays every Sunday.

## Live Demo
**to be added**

---

## Key Features

- **Multi-Platform Support**: Optimized for S23 Ultra (Mobile), PC/Mac Browsers, and Smart TVs.
- **Professional Umpire**: High-quality voice announcements for scores, deuce, advantage, and game wins.
- **Smart Hardware Integration**: Control the entire app using a single button (Bluetooth remote/earpiece) or a numeric keypad.
- **Multiple Scoring Modes**:
    - **Deuce**: Standard tennis rules.
    - **Golden Point**: Fast-paced "no-ad" scoring.
    - **16/24/32 Points**: Total point-based scoring "Americano" style.
- **Persistent Memory**: Remembers your scoring mode even after a page refresh.
- **Immersive View**: One-click Fullscreen (MAX) mode to remove browser clutter.

---

## How to Run

Open the URL [http://judhi.github.io/madel_score/] and that's it!

## How to Control

### 1. The Universal Remote (ENTER Key)
If you are using a single-button Bluetooth remote or earpiece:
* **1 Click**: Score a point for **YOU**.
* **2 Clicks**: Score a point for **OPPONENT**.
* **3 Clicks**: **UNDO** last action.
* **4 Clicks**: **REPORT** current status (Game & Set).
* **First Click**: Wakes up the Umpire.

### 2. Numeric Keypad / Keyboard
For use with a mini-keypad or laptop:
* `1`: Point for **YOU**
* `2`: Point for **OPPONENT**
* `3`: **UNDO**
* `4`: **REPORT** Status
* `5`: Toggle **FULLSCREEN**
* `0`: Cycle **SCORING MODES**
* `9`: **RELOAD** App

### 3. Touch Screen
For use with mobile phone/tablet without remote or keyboard. 
Just touch the buttons or score on the screen.

---

## 🛠️ Technical Details
- **Collaboration**: Google Gemini to generate the codes based on the author's vision
- **Engine**: Pure HTML5, CSS3, and Vanilla JavaScript.
- **API**: Utilizes the **Web Speech API** for professional vocal synthesis and the **Fullscreen API** for immersive display.
- **Safety**: Includes a 1-second "Input Lockdown" after each point to prevent accidental double-scoring from hardware button bounces.

---

** This project combines my passion for sports with efficient human-computer interaction (HCI) logic.

*Created for the Padel Community. May your lobs be high and your smashes be fierce.*
