# 🕐 Pie Clock - Interview Timer Component

A sleek, interactive doughnut-style interview timer and schedule visualizer. Built with Chart.js, featuring real-time countdowns, color-coded urgency, and dynamic candidate markers.

## 🔗 Live Preview
**[Check out the Live Demo here!](https://guanine96.github.io/PieClock/)**

---

![Tech](https://img.shields.io/badge/tech-Vanilla%20JS%20|%20Chart.js-orange)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

- **Visual Countdown:** See exactly how much time is left until the next interview.
- **Dynamic Urgency Colors:** The clock automatically shifts colors based on proximity to the appointment:
  - 🔵 **Blue:** More than an hour away.
  - 🟡 **Yellow:** Less than 60 minutes remaining.
  - 🔴 **Red:** Final 15-minute warning!
  - 🟢 **Green:** Interview is currently "Now."
- **Interactive Markers:** Scheduled interviews are plotted around the clock face using trigonometric positioning.
- **Hover Tooltips:** Get candidate details (Name, Position, Source) instantly by hovering over the markers.
- **Real-time Mode:** When no interview is selected, it displays the current time and the percentage of the day passed.

## 🚀 Quick Start

To use this component in your project, simply include the script and the HTML structure:

1. **Include Chart.js:**
   ```html
   <script src="[https://cdn.jsdelivr.net/npm/chart.js](https://cdn.jsdelivr.net/npm/chart.js)"></script>
