# 💰 FlexiCalc — Dynamic Loan & Amortization Engine

A sleek, responsive, zero-dependency financial web application that calculates Loan EMIs (Equated Monthly Installments), provides visual payment breakdowns, generates full amortization schedules, and supports multi-currency inputs with custom theme switching.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 🌟 Key Features

- **Unconstrained Inputs:** Supports calculations for any loan amount, interest rate, or tenure without rigid upper boundaries—ideal for high-net-worth calculations across global currencies.
- **Dynamic Auto-Scaling Sliders:** Range sliders automatically resize their bounds (`K`, `M`, `B`) as custom values are typed into numerical fields.
- **Multi-Currency Support:** Type or choose any custom currency symbol (`$`, `€`, `£`, `₹`, `¥`, `R`, etc.) to format the entire dashboard instantly.
- **Dynamic Theme Switcher:** Features 5 custom themes built with native CSS Custom Properties (`Dark Minimal`, `Emerald Green`, `Cyberpunk Neon`, `Midnight Blue`, and `Clean Light`).
- **Data Visualization:** Pure SVG donut chart dynamically updates to visualize the ratio of Principal vs. Total Interest paid over time.
- **Amortization Breakdown & CSV Export:** Generates a month-by-month payment schedule detailing interest paid, principal paid, and remaining balance, with one-click **CSV download**.
- **Zero External Dependencies:** Built entirely with native HTML5, CSS3, and JavaScript ES6+ for maximum performance and instant load times.

---

## 🧮 Mathematical Formula

The application calculates monthly installments using the standard financial EMI equation:

EMI=P⋅R⋅(1+R)N(1+R)N−1EMI
= \frac{P \cdot R \cdot (1 + R)^N}{(1 + R)^N - 1}EMI=
(1+R)N−1P⋅R⋅(1+R)N, 

where:
P: Principal amount.
R: Interest rate per month.
N: Number of months (loan tenure).

### Additional Metrics Calculated:
- **Total Amount Payable:** $\text{EMI} \times N$
- **Total Interest Payable:** $\text{Total Amount Payable} - P$

---

## 🛠️ Built With

- **HTML5:** Semantic structural layout and accessibility elements.
- **CSS3:** Custom CSS variables for instant theme toggling, Flexbox/Grid responsive UI.
- **Vanilla JavaScript (ES6+):** DOM manipulation, state handling, mathematical algorithms, SVG rendering, and Blob-based CSV generation.

---

## 🚀 Quick Start

No installation or build steps required!
