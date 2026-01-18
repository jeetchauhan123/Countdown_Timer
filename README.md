# Countdown Timer ⏳

A simple **Countdown Timer** built with **HTML, CSS, and JavaScript**.  
It shows the remaining time (days, hours, minutes, seconds) until a specific end date and displays a progress bar showing how much time has passed since the start date.

---

## 🔥 Features

- Displays countdown in **days, hours, minutes, and seconds**
- Shows a **progress bar** indicating the percentage of time passed
- Automatically stops and displays **"EXPIRED"** when the time ends
- Smooth progress bar animation using CSS

---

## 🧠 How It Works

- The timer calculates the difference between the **end date** and **current date**
- It updates every second using `setInterval()`
- It calculates:
  - Remaining time
  - Total duration
  - Percentage completed
- Updates the UI accordingly

---

## 📁 Files Included

- `index.html` — HTML structure  
- `CountdownTimer.css` — Styling  
- `CountdownTimer.js` — Countdown logic  

---

## 🚀 How to Run

1. Clone the repository or download the project folder  
2. Open the folder in your code editor  
3. Open `index.html` in your browser  
   *(or use Live Server for live reload)*  

---

## 🛠️ Customization

You can change the countdown dates in `CountdownTimer.js`:

```js
const enddate = new Date("30 jun 2030 15:00:00").getTime();
const startdate = new Date("17 jun 2024 00:00:00").getTime();
