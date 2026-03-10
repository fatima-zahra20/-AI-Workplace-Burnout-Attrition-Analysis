# -AI-Workplace-Burnout-Attrition-Analysis
As AI reshapes the modern workplace, one question becomes critical: is it helping us — or burning us out?
[README.md](https://github.com/user-attachments/files/25856107/README.md)
# 🤖 AI Workplace Burnout & Attrition Analysis

> *"After testing salary, remote work, education, and AI usage — only one thing truly predicts burnout: whether your work means something to you."*

---

## 📌 Project Overview

As AI reshapes the modern workplace, one question becomes critical: **is it helping us — or burning us out?**

This project analyzes 500+ tech employees across 10 countries to uncover what truly drives burnout, attrition risk, and job satisfaction in an AI-first work environment.

---

## 🔍 Questions Explored

| # | Question | Key Finding |
|---|---|---|
| 1 | Which job roles are most at risk from AI? | Backend Engineers face 44% task replacement |
| 2 | Do more educated employees fear AI less? | Education level has NO effect on fear of AI |
| 3 | Do self-taught employees burn out more? | Slightly higher burnout — but difference is minimal |
| 4 | Does AI tool usage increase productivity or burnout? | Productivity: yes (r=0.31). Burnout: not at all (r=0.00) |
| 5 | Do remote workers experience different burnout? | No — all work types show nearly identical burnout |
| 6 | Do higher salaries protect against burnout? | No consistent pattern — salary doesn't explain burnout |
| 7 | Which country has the highest attrition risk? | UK leads, followed by Australia and Germany |
| 8 | Is there a relationship between burnout and satisfaction? | Strong negative correlation (r=-0.63) |
| 9 | Is there a sweet spot of AI usage for productivity? | No clear sweet spot — differences are minimal |

---

## 💡 Key Takeaway

After testing 5 potential causes of burnout — remote work, salary, education level, AI tool usage, and AI hours — **none of them meaningfully explain burnout.**

Only **job satisfaction** showed a strong relationship (r=-0.63).

> *Burnout is not about how much you work with AI, how much you earn, or where you work from. It's about whether your work means something to you.*

---

## ⚠️ Analytical Note

Each question in this analysis examines one factor at a time. In reality, burnout, productivity, and fear of AI replacement are influenced by multiple variables simultaneously. These findings should be interpreted as **patterns and signals** — not definitive causes.

A deeper multivariate regression analysis would be required to truly untangle the root causes of burnout.

---

## 🛠️ Tools & Libraries

- **Python** — core analysis
- **Pandas** — data cleaning and manipulation
- **Matplotlib / Seaborn** — visualizations
- **SQLite** — SQL queries

---

## 📁 Project Structure

```
ai-workplace-burnout-analysis/
│
├── ai_worker_burnout.ipynb   # Main analysis notebook
├── ai_worker_burnout_attrition_2026.csv        # Dataset
├── requirements.txt                     # Dependencies
└── README.md                            # This file
```

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/fatima-zahra20/ai-workplace-burnout-analysis

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook ai_worker_burnout.ipynb
```

---

## 📊 Dataset

- **Source:** Kaggle — AI Worker Burnout & Attrition Risk Dataset
- **Size:** 500+ employees across 10 countries
- **Features:** Job role, education, remote work type, AI tool usage, burnout score, job satisfaction, attrition risk and more

---

## 👩‍💻 About

Built by **Fatima Zahra BOUTKHIL ** — a self-taught data analyst 

Passionate about extracting meaningful insights from data and telling stories that matter.

[![GitHub](https://img.shields.io/badge/GitHub-fatima--zahra20-black?logo=github)](https://github.com/fatima-zahra20)
