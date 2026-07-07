# 🇮🇳 India Tech Brain Drain Decoder

> *Are Indian developers being fairly valued — or leaving to find better pay abroad?*

A data analysis project using the **Stack Overflow Developer Survey 2024** to uncover salary gaps, skill premiums, and career levers for Indian software developers.

---

## 📊 What This Project Analyzes

| Question | Chart |
|---|---|
| How big is the India vs global salary gap? | Salary Distribution |
| Which programming languages close the gap most? | Language Pay Gap |
| Does education level affect Indian dev salaries? | Education vs Salary |
| Does the gap grow or shrink with experience? | Experience Curve |
| Does remote work help Indian devs earn more? | Remote Work Premium |

---

## 🔍 Key Findings

1. **The gap is real** — Indian developers earn significantly less than global counterparts with the same skills
2. **Language choice matters** — Some languages have a much smaller pay gap than others
3. **Remote work is the biggest lever** — Remote Indian devs out-earn in-person peers by a wide margin
4. **Experience helps, but doesn't close the gap** — The percentage gap remains relatively stable across experience levels
5. **Education has diminishing returns in India** — Skills and tech stack matter more than degree level

---

## 🛠️ Tech Stack

- **Python 3.11+**
- **pandas** — data cleaning and analysis
- **matplotlib + seaborn** — visualizations
- **Jupyter Notebook** — interactive analysis

---

## 🚀 How to Run

```bash
# 1. Clone this repo
git clone https://github.com/YOUR_USERNAME/brain-drain-project.git
cd brain-drain-project

# 2. Install dependencies
pip install -r requirements.txt

# 3. Download the dataset
# Go to https://stackoverflow.com/research and download survey_results_public.csv
# Rename it to results.csv and place it in this folder

# 4. Open the notebook
jupyter notebook analysis.ipynb
```

---

## 📁 Project Structure

```
brain-drain-project/
├── analysis.ipynb              ← Main notebook (run this)
├── results.csv                 ← Dataset (download separately)
├── requirements.txt            ← Python dependencies
├── README.md                   ← This file
└── charts/                     ← Auto-generated charts
    ├── chart1_salary_distribution.png
    ├── chart2_language_gap.png
    ├── chart3_education_salary.png
    ├── chart4_experience_salary.png
    └── chart5_remote_salary.png
```

---

## 📈 Charts Preview

Charts are generated automatically when you run the notebook. Each is saved as a high-resolution PNG.

---

## 📌 Data Source

- **Stack Overflow Developer Survey 2024** — [stackoverflow.com/research](https://stackoverflow.com/research)
- ~65,000 professional developer responses worldwide
- Free to use for analysis (ODbL license)

---

## 👤 Author

**Vaishnavi Tiwari**
- Built as a portfolio data analysis project
- Connect on [LinkedIn](#) | [GitHub](#)

---

*If you found this interesting, give it a ⭐ on GitHub!*
