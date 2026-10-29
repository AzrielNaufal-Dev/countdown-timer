# ⏳ Countdown Timer

A responsive and interactive web-based Countdown Timer built using **Vanilla JavaScript**, **HTML5**, and **CSS3**. This application allows users to input custom hours, minutes, and seconds to start a real-time dynamic countdown.

![Tech Stack](https://img.shields.io/badge/Tech%20Stack-HTML5%20%7C%20CSS3%20%7C%20JavaScript-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## ✨ Features

- **Custom Input Support:** Set hours, minutes, and seconds dynamically.
- **Formatted Display:** Uses zero-padding (`00`) for single-digit numbers for a clean dashboard UI.
- **Auto-Reset Prevention:** Automatically clears existing timers when starting a new countdown to avoid overlap bugs.
- **Completion Alert:** Notifies users instantly when the time reaches zero.
- **Responsive Design:** Clean, modern layout centered with CSS Flexbox.

---

## 🛠️ Tech Stack & Concepts Applied

- **HTML5:** Semantic layout structure and input validation (`min` / `max` constraints).
- **CSS3:** Custom styling, Flexbox layout, and hover micro-interactions.
- **Vanilla JavaScript (ES6+):**
  - DOM Manipulation & Event Handling
  - Time conversions (Seconds $\leftrightarrow$ Hours/Minutes/Days)
  - `setInterval()` & `clearInterval()` for interval management
  - `.padStart(2, "0")` for consistent two-digit display strings

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AzrielNaufal-Dev/countdown-timer.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd countdown-timer
   ```
3. **Open `index.html`** in your browser or run it using VS Code's **Live Server** extension.

---

## 📝 Author

Created with 💡 by **Azriel Naufal**