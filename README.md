# 📊 Smart Attendance Calculator

A professional-grade web utility designed to help students track their academic attendance and manage their schedules effectively. This tool goes beyond basic calculation by providing actionable insights into attendance shortfalls.

---

## 🚀 Key Features

* **Real-Time Analytics:** Instantly calculates attendance percentage based on total and attended sessions.
* **Predictive 'Danger Zone' Logic:** Automatically determines the exact number of consecutive classes required to reach the target threshold (e.g., 75%).
* **Intuitive UI/UX:** Features a modern, high-contrast dashboard for better readability and focus, as seen in the "Vibe Coding" design.
* **Status Indicators:** Visual feedback (Safe vs. Danger Zone) to help students make informed decisions.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Modern Flexbox/Grid Layouts)
* **Logic:** JavaScript (ES6+) / Python (Flask Backend)
* **Styling:** Custom CSS with a focus on dark-mode aesthetics.

## 📖 How It Works

1.  **Input:** User enters the `Total Classes` conducted and `Classes Attended`.
2.  **Processing:** The algorithm calculates the current percentage:
    $$\text{Percentage} = \left( \frac{\text{Attended}}{\text{Total}} \right) \times 100$$
3.  **Gap Analysis:** If the percentage is below the target (75%), it calculates the "Required Classes" to exit the 'Danger Zone'.
4.  **Output:** Displays the status and the specific number of classes needed to reach the goal.

## 🔧 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/smart-attendance-calculator.git](https://github.com/YOUR_GITHUB_USERNAME/smart-attendance-calculator.git) 
