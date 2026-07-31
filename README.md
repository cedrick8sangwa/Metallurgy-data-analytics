# 🏭 Metallurgy Data Analytics: Copper Loss Reduction in Slag

> Python data analysis and Lean Six Sigma (DMAIC) framework applied to optimize pyrometallurgical smelting processes and reduce copper losses in slag.

## 📌 Project Overview
In pyrometallurgical copper smelting, excessive copper loss in the slag phase represents a significant economic and environmental inefficiency. This project investigates the root causes of these losses—specifically focusing on the degradation of coke quality—using a data-driven approach. 

By combining Pyrometallurgy, Data Science (Python), and the Six Sigma DMAIC methodology, this repository provides a structured analytical framework to identify, quantify, and resolve metallurgical inefficiencies.

---

## 🛠️ Methodology: The DMAIC Framework

This project follows the Lean Six Sigma DMAIC cycle:

### 1. Define (D)
* Problem: Increase in copper (Cu) percentage in the discard slag due to variable coke quality (reducing agent & heat source).
* Objective: Reduce Cu losses in slag from > 1.8% to < 0.8% and stabilize the smelting process.

### 2. Measure (M)
* Data Collection: Compiled historical and operational data, including:
  * Coke parameters:  Fixed Carbon,  Ash, Moisture, Granulometry.
  * Slag parameters:  Cu, Viscosity indicators, Temperature, Basicity ratio (CaO/SiO2).
  

### 3. Analyze (A) (Python EDA & Statistical Testing)
* Utilized Python (pandas, scipy.stats, matplotlib) to perform Exploratory Data Analysis (EDA).
* Key Insights: Differentiated between chemical losses (dissolved Cu2O due to insufficient reducing conditions) and mechanical entrainment (copper droplets trapped due to high slag viscosity caused by excessive coke ash).
* Correlation: Conducted multiple linear regression to isolate the most impactful variables on slag Cu content.
  ![Slag Analysis SPC Charts](https://github.com/user-attachments/assets/2977c367-2041-4634-9bfb-b52da8f07cc4)

### 4. Improve (I)
* Process Optimization: Calculated dynamic flux addition models to adjust for varying coke ash content, maintaining optimal slag fluidity.
* Recommendations: Coke screening to remove fines and adjustments to the carbon feed rate based on incoming fixed carbon analysis.

### 5. Control (C)
* Statistical Process Control (SPC): Developed automated Control Charts (X-bar & R charts) to monitor slag $Cu$ content and furnace temperature in real-time.
* Standard Operating Procedures (SOPs): Updated dynamic compensation tables for operators based on real-time coke quality inputs.

---

## 💻 Tech Stack & Tools
* Programming Language: Python 3.x
* Data Manipulation & Analysis: pandas, NumPy
* Statistical Modeling & Machine Learning: Scikit-Learn, SciPy
* Data Visualization: Matplotlib, Seaborn
* Process Engineering: Lean Six Sigma (Green Belt), Metallurgical Thermodynamics

---

## 🚀 How to Run the Project
```bash
git clone https://github.com/cedrick8sangwa/Metallurgy-data-analytics.git
```
