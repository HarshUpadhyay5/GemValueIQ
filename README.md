# 💎 GemValueIQ — Diamond Quality & Market Insights

## 📌 Overview
Diamonds aren’t just sparkly rocks — their market value is shaped by a delicate interplay of quality, physical characteristics, and market perception.  
This project explores a **53,940-record dataset** of diamonds to uncover how **cut, color, clarity, and carat** influence **pricing**.  
The analysis is supported by **interactive Power BI dashboards** designed to help **jewelers, investors, and enthusiasts** make informed decisions.

---

## 📊 Dataset Details
- **Source:** Diamonds dataset (53,940 entries, 10 features)  
- **Key Features:**
  - **Carat** — Weight of the diamond
  - **Cut** — Quality of cut *(Ideal, Premium, Very Good, Good, Fair)*
  - **Color** — Diamond color grade *(D = best, J = lowest)*
  - **Clarity** — Diamond clarity scale *(IF, VVS1, VVS2, VS1, VS2, SI1, SI2, I1)*
  - **Depth, Table** — Physical proportions
  - **x, y, z** — Dimensions in mm
  - **Price** — USD market price

---

## 📈 Key KPIs & Insights

### **1. Physical Characteristics**
- **Average Carat:** `0.80`
- **Average Depth Percentage:** `61.75%`
- Most diamonds fall between **0.2 – 2.5 carats**.
- Larger diamonds (>3 carats) are rare and command premium prices.

---

### **2. Cut & Color Analysis**
- **Most common color:** `G` (~4.9K diamonds)
- **Highest average price color:** `J` (~$5,323), surprisingly higher than D.
- **Premium** and **Fair** cuts have the **highest average prices** (~$4.6K & $4.4K).

💡 *Insight:* Pricing doesn’t always align perfectly with the GIA grading hierarchy. Market factors and size influence more than theoretical grading.

---

### **3. Clarity & Market Value**
- **Highest avg price by clarity:** `SI2` (~$5.1K) — driven by large carat weights despite lower clarity.
- **Lowest avg price clarity:** `VVS1` (~$2.5K) — suggests smaller stones dominate this category.

💡 *Impact:* For commercial buyers, **balancing carat size and acceptable clarity** often yields better ROI than aiming for flawless clarity.

---

### **4. Price Distribution**
- Strong skew toward **lower-priced diamonds** (most < $5K).
- Clear linear trend between **carat & price**, but with high variance at larger sizes.

---

## 🛠 Tools & Technologies
- **MS SQL Server** — Data storage and querying
- **Power BI** — Interactive dashboards
- **Python (Pandas, Matplotlib)** — Data cleaning & preprocessing
- **CSV Dataset** — Source data file
- **.pbix File** — Power BI report

---

## 📂 Repository Structure
- **GemValueIQ/**
  - **diamonds.csv** — Raw dataset
  - **Diamonds_Quality_Market.pbix** — Power BI dashboard
  - **screenshots/**
    - quality_characteristics.png
    - market_value_trends.png
  - **README.md** — Project documentation



---
## 📌 Business Implications
- **Retailers:** Can stock based on the sweet spot of **price vs. desirability**.
- **Investors:** Identify underpriced categories with strong resale potential.
- **Consumers:** Understand trade-offs between **carat, cut, clarity, and color** to maximize purchase value.
