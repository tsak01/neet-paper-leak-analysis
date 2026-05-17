# NEET Paper Leak Detection | Statistical Analysis

Analysed simulated NEET exam data to detect fraudulent centres 
using 5 statistical concepts.

## What I built
- Simulated 1,000 students across 10 exam centres
- Hid fraud in 2 centres using realistic score and time patterns
- Used statistics to surface them without any labels

## Methods Used
- Mean / Median analysis
- Standard Deviation
- Correlation (Pearson r)
- Normal Distribution (Shapiro-Wilk)
- Hypothesis Testing (Welch's T-test)

## Result
Both compromised centres flagged correctly.  
Precision: 100% | Recall: 100% | F1: 1.0

## Tools
Python | pandas | numpy | scipy | matplotlib

## Dashboard
![Dashboard](NEET_Summary_Dashboard(1).png)

---

## How to Run

1. Open the notebook in Google Colab
2. Run all cells top to bottom — no external data needed
3. Dataset is generated in Cell 2
4. All charts and the final verdict table generate automatically

---

## Tools & Libraries

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `SciPy` · `Google Colab`

---

## Key Takeaway

This project is not about machine learning or complex models.
It shows that clear statistical thinking — applied consistently across multiple signals —
is enough to catch fraud that affected millions of students.

That is what data analytics is for.

---

*Inspired by the NEET 2026 paper leak controversy, India*
*Project by Sakshi Tawte*
