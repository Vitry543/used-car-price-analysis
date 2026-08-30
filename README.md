# used-car-price-analysis
# 🚗 CarDekho Used Car Data Analysis & Valuation Insights

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-38BDF8.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

An end-to-end Exploratory Data Analysis (EDA) project evaluating pre-owned vehicle pricing dynamics, value retention, and key depreciation drivers using the **CarDekho** dataset.

---

## 📌 Project Overview

In the pre-owned automobile industry, accurate vehicle pricing is complex due to competing variables such as age, total mileage, engine fuel type, transmission choice, and sales channel. Inaccurate pricing leads to holding costs for dealers and valuation asymmetry for buyers.

This project analyzes **301 vehicle listings** to uncover critical factors driving market valuation and provides actionable insights for pricing optimization.

---

## 🎯 Key Business Questions Addressed

1. **Value Retention:** How sharply does vehicle age impact resale price?
2. **Engine Choice Premium:** How do resale dynamics differ across Diesel, Petrol, and CNG vehicles?
3. **Driving Convenience:** What is the market value premium for Automatic vs. Manual transmissions?
4. **Market Channel Dynamics:** How do Dealer listing prices compare against direct Individual seller listings?

---

## 📊 Core Findings & Analytics

* ⛽ **Fuel Type Premium:** **Diesel vehicles** command the highest average selling price (**₹10.28 Lakhs**), significantly outperforming **Petrol** (**₹3.26 Lakhs**) and **CNG** (**₹3.10 Lakhs**) due to strong long-distance and commercial demand.
* 🏬 **Seller Channel Disparity:** **Dealer listings** average **₹6.72 Lakhs**, whereas **Individual listings** average **₹0.87 Lakhs**, reflecting differences in vehicle condition, refurbishment, and dealer markup.
* ⚙️ **Transmission Advantage:** Automatic transmission models hold a noticeable pricing premium over Manual counterparts across comparable vehicle ages.
* 📉 **Depreciation Rate:** Pre-owned vehicles experience an average baseline depreciation of **~38.9%** relative to their original showroom price (`Present_Price`).

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python 3.x
* **Data Processing & Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `seaborn`, `matplotlib`
* **Environment:** Jupyter Notebook / VS Code

---

## 📁 Repository Structure

```text
├── car_Dekho_DA.csv          # Raw Used Car Dataset (301 entries, 9 columns)
├── car_dekho_analysis.ipynb     # Complete EDA and Visualization Script
├── images/                   # Exported visual plots for PPT and Documentation
│   ├── fuel_type_dynamics.png
│   └── seller_channel_variance.png
└── README.md                 # Project documentation
