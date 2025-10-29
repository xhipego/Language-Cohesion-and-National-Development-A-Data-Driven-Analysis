# 🌍 Language Coordination and National Development

This project investigates the correlation between **linguistic diversity** and **national development**, introducing a new measure — the **Language Coordination Capacity (LCC)** Index — as a potential baseline indicator for socioeconomic progress.

---

## 🧩 Research Hypothesis
> Linguistic coordination serves as a baseline for development: nations with high Language Coordination Capacity (LCC) exhibit stronger socioeconomic indicators.

---

## 📊 Data and Variables
| Variable | Description |
|-----------|--------------|
| GDP_per_Capita | Economic output per person |
| HDI | Human Development Index |
| Languages_spoken | Total recognized languages |
| Population_millions | Country population size |
| LCC | Language Coordination Capacity = Population / Languages_spoken |

---

## ⚙️ Methods
1. **Descriptive Analysis** — Distribution of languages and GDP across countries.  
2. **Correlation Analysis** — Pearson correlations between LCC, GDP, HDI, and Languages.  
3. **Clustering (K-Means)** — Natural grouping of countries based on LCC and development indicators.  
4. **Feature Importance** — Identifying the most predictive variables for development outcomes.

---

## 📈 Results Summary
- Countries clustered naturally into two groups:
  - **Cluster 1:** High LCC, High GDP (Developed nations)
  - **Cluster 2:** Low LCC, High linguistic diversity (Underdeveloped nations)
- **Feature importance:** GDP_per_Capita ranked highest, followed by Languages_spoken.
- **Correlations:**  
  - Languages ↔ Population: 0.66  
  - Languages ↔ GDP_per_Capita: 0.60  
- **Outliers:**  
  - *China* — many languages but high LCC (Mandarin majority).  
  - *Burundi* — few languages but low GDP (unity ≠ automatic development).

---

## 📚 Files Overview
- `notebooks/` – Jupyter notebooks for analysis and visualization  
- `src/` – Core Python scripts for LCC computation, clustering, and plotting  
- `data/` – Raw and processed datasets  
- `paper/` – LaTeX-formatted research paper (`main.tex`)  
- `results/` – Exported plots and figures  

---

## 🧠 Key Insight
Language cohesion does not guarantee development — but it provides the **baseline** upon which coordinated national progress is built.

---

## 🧩 Dependencies
To install requirements:
```bash
pip install -r requirements.txt
