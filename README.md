# Trash & Treasure: How Wealth Tracks Plastic Mismanagement 🌍♻️

A short data-story project exploring how **GDP per capita** relates to **mismanaged plastic waste per person** across countries (focus year: **2019**). Built with Python + Jupyter, using publicly available datasets from **Our World in Data (OWID)**.

---

## 🔎 Research Question
**Do wealthier countries mismanage less plastic waste per person, or does economic growth shift the problem elsewhere?**

---

## 📌 Key Takeaways (High-level)
- The relationship in 2019 suggests an **inverse trend**: countries with higher GDP per capita tend to have **lower mismanaged plastic waste per person**.
- The pattern is not universal—**middle-income outliers** demonstrate that **policy + infrastructure** can matter as much as income.

---

## 📊 What’s in the Notebook
The analysis includes 8 visuals (as labeled in the notebook):

- **Figure 1** — Histogram: distribution of mismanaged plastic waste per capita (2019)
- **Figure 2** — KDE: distribution of GDP per capita (PPP, 2019)
- **Figure 3** — Scatter: GDP vs mismanaged plastic waste (2019)
- **Figure 4** — Scatter + regression line (trend)
- **Figure 5** — Annotated scatter: highest mismanaged waste countries + U.S. reference
- **Figure 6** — Boxplot by GDP quartile (**log scale** for fair comparison)
- **Figure 7** — Revised “perception-first” scatter (axes at zero, density color encoding)
- **Figure 8** — Summary visualization with medians + trend line

---

## 🧰 Tech Stack
- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib

---

## 📦 Data Sources
This project uses OWID datasets:
- **Mismanaged plastic waste per capita (kg per year)**
- **GDP per capita, PPP (constant 2021 international $)**

### Expected local files
The notebook currently reads these CSVs from the project root:
- `mismanaged-plastic-waste-per-capita.csv`
- `gdp-per-capita-worldbank.csv`

> If you prefer putting them in a `data/` folder, either move the files to the root or update the `pd.read_csv(...)` paths accordingly.

---

## ▶️ How to Run
### 1) Clone the repo
```bash
git clone <YOUR_REPO_URL>
cd <YOUR_REPO_NAME>

