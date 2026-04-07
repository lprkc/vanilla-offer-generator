# 🩺 Physician Offer & Total Cash Compensation (TCC) Modeler

A professional, open-source tool designed specifically for physicians to evaluate and compare employment offers. This generator focuses on **Total Cash Compensation (TCC)**, modeling production-based pay (wRVUs), clinical load, and long-term financial projections.

## 🚀 Live Demo
**[(https://lprkc.github.io/vanilla-offer-generator/]**

---

## ✨ Key Features

- **Physician-Specific Logic:** Unlike standard salary calculators, this tool models **wRVU Production** (Base + Threshold + Conversion Factor).
- **Clinical Load Analysis:** Automatically calculates your **effective hourly rate** based on FTE status, clinical hours per week, and net weeks worked per year.
- **Dual Branding:** 
    - **Creator Brand:** Hardcode your own logo into the header.
    - **User Brand:** Allows physicians to upload the logo of the hospital/system they are evaluating for a professional, branded report.
- **4-Year Cumulative Forecast:** Visualizes the "stickiness" of an offer by showing total earnings over a standard 4-year contract term.
- **Privacy First:** No data ever leaves the user's browser. All calculations and image processing happen locally.
- **Export to PDF:** A "Print-to-PDF" optimized layout for saving and sharing offer comparisons.

---

## 🛠️ How to Customize (For the Developer)

To brand this tool as your own before publishing:

1. **Change the Creator Logo:**
   Open `index.html` and locate the following line (around line 22):
   ```html
   <img src="https://via.placeholder.com/120x40?text=MY+LOGO" alt="Logo" class="h-8">
