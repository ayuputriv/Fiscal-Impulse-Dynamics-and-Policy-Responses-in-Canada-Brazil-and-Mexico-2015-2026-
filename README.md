# **Fiscal Impulse Analysis Repository**

# Fiscal Impulse Analysis & Trade War Impact

### *Canada, Brazil, and Mexico (2015–2026)*

Quantitative fiscal stance modeling, GDP-based forecasting, and cross-country macroeconomic analysis.
*Author: Ayu Putri Vidiantiwi*

---

## **Overview**

This project analyzes the fiscal stance of **Canada, Brazil, and Mexico** from 2015–2026 using **fiscal impulse calculations** and **GDP-based seasonal projection models**.
The analysis evaluates how each country adjusted its fiscal strategy during major shocks—including **COVID-19** and the hypothetical **Trump 2.0 trade war scenario (2025)**.

The study integrates:

* Fiscal impulse estimation
* Real GDP forecasting
* Cross-country policy comparison
* Impact assessments for tariffs, inflation, and growth
* Policy response analysis using official data and global institutions

Full report: *Strategi Fiskal Kanada, Brazil, Meksiko* 
Notebook: *Fiscal Impulse Brazil, Canada, Mexico (1996–2025).ipynb*

---

## **Objectives**

This project aims to:

* Compute quarterly **fiscal impulse** for Canada, Brazil, and Mexico.
* Identify shifts between **expansionary vs. contractionary** fiscal stances.
* Analyze policy responses during global shocks (pandemic & trade war).
* Forecast fiscal impulse for **2025–2026** using historical seasonal patterns.
* Evaluate macroeconomic resilience and policy effectiveness across countries.

---

## **Methodology**

### **1. Data Sources**

* Real & nominal GDP series
* Government primary balance
* Cyclically-Adjusted Primary Balance (CAPB)
* Policy documents (OECD, IMF, central bank reports)
* Fiscal package announcements (COVID-19, tariff responses)

### **2. Fiscal Impulse Formula**

```text
Fiscal Impulse = -1 × (Δ Cyclically-Adjusted Primary Balance)
```

Interpretation:

* **Positive** → Expansionary fiscal stance
* **Negative** → Contractionary stance

### **3. Forecasting Approach**

To estimate fiscal impulse for **2025–2026**, the project uses:

* Historical quarterly GDP patterns (1996–2025)
* Proportional allocation modeling
* Baseline + risk scenarios for the Trump 2.0 tariff shock
* Manual adjustments for policy announcements

This method preserves **seasonal patterns** while incorporating **forward-looking macro assumptions**.

---

## **Key Findings**

### 🇨🇦 **Canada: Adaptive, Countercyclical Policy**

* Contractionary pre-COVID, aggressively expansionary in Q3 2020 (FI = +4.67).
* Tightened again during 2022–23, then expanded in 2024–26.
* 25% U.S. tariff shock triggers additional stimulus and infrastructure spending.
* Fiscal impulse remains **positive through 2025–26**, preventing deeper GDP contraction.

### 🇧🇷 **Brazil: Debt-Driven Fiscal Tightening**

* Frequent contraction due to rising debt (~92% of GDP in 2025).
* COVID stimulus delayed; only Q3–Q4 2020 shows expansion.
* 2025–26: Brazil **returns to tightening** to pursue primary surplus targets.

### 🇲🇽 **Mexico: Conservative, “No-New-Debt” Policy**

* One of the most contractionary fiscal stances globally (2015–2024).
* Minimal COVID stimulus (1–2% of GDP).
* Even with 25% U.S. tariffs, Mexico limits fiscal expansion → slower recovery.
* GDP projected to stagnate around **0.4% in 2025**.

All insights are derived from the attached country analysis report. 

---

## **Visualizations**

Included in the notebook:

* Fiscal impulse timeline per country
* Combined fiscal stance comparison
* Tariff impact summary table
* GDP forecast lines for 2025–2026
* Quarterly fiscal impulse heatmaps

---

## **Repository Structure**

```
📁 fiscal-impulse-analysis
│
├── 📄 README.md
├── 📓 fiscal_impulse_analysis.ipynb
├── 📄 Strategi_Fiskal_Kanada_Brazil_Meksiko.pdf
└── 📁 data/
    ├── gdp_canada.csv
    ├── gdp_brazil.csv
    ├── gdp_mexico.csv
    ├── capb_canada.csv
    ├── capb_brazil.csv
    ├── capb_mexico.csv
```

---

## **Skills Demonstrated**

### **Technical**

* Time-series modeling
* Fiscal impulse computation
* Feature engineering for macro data
* Data cleaning & transformation
* Visualization (matplotlib / seaborn)

### **Analytical**

* Macroeconomic interpretation
* Policy evaluation under global shocks
* Country comparison & evidence-based insights
* Forecasting under uncertainty

### **Communication**

* Clear structured fiscal analysis
* Executive-level policy narrative
* Country-level economic storytelling

---

## **Tools Used**

* Python: pandas, NumPy, matplotlib
* Quantitative Methods: Time-series analysis, CAPB adjustment, fiscal impulse computation
* Policy Analysis: Cross-country comparative frameworks, shock interpretation
* Economic Sources: IMF, OECD, Banxico, Bank of Canada, Brazil Central Bank

---

## 👩🏻‍💻 About Me

**Ayu Putri Vidiantiwi**  
* 📚 M.S. in Applied Analytics, Columbia University  
* 📊 Passionate about finance, business, data storytelling, and analytics
* 🌐 LinkedIn - https://www.linkedin.com/in/ayuputriv/
* 📧 ayu.vidiantiwi@columbia.edu
