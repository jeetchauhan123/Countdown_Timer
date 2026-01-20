# Countdown Timer ⏳

A clean and simple **Countdown Timer** built using **HTML, CSS, and JavaScript**.  
It displays the remaining time until a specified end date and shows a progress bar representing how much time has passed since a start date.

---

## 🔥 Features

- Countdown display in **days, hours, minutes, and seconds**
- **Progress bar** shows the percentage of time elapsed
- Automatically stops and displays **"EXPIRED"** when the countdown ends
- Smooth animation for the progress bar

---

## 🧠 How It Works

- The script calculates the difference between the **end date** and the **current time**
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

## 🚀 Live Demo

Check it out here:  
**https://countdown-timer-black-six.vercel.app/**

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
```

## 📌 Notes

- Ensure the dates are in a valid format for `Date()`.
- The progress bar will only work correctly if both start and end dates are valid and the current time is between them.

---

## 🧩 License

This project is open-source and free to use.

---

Enjoy your countdown timer! ⏱️
