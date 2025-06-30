# 🗽 U.S.-Headquartered S\&P 500 Companies: A Data Analysis Project

Welcome to my data analysis project focused on the **S\&P 500 companies headquartered in the United States**. This analysis filters and refines data from a broader dataset to present insights specifically about American-based corporations listed in the S\&P 500 index.

## 📊 Overview

This project demonstrates a complete data wrangling and analysis pipeline—from **data sourcing** to **cleaning**, **transformation**, and **filtering**—with the goal of isolating and exploring **U.S.-based companies** in the S\&P 500 index.

---

## 🔍 Objectives

* ✅ Gather data from a reliable online source (Wikipedia)
* ✅ Clean and refine the dataset for relevance and clarity
* ✅ Transform the data using calculated and conditional columns
* ✅ Perform string manipulation for uniformity and filtering
* ✅ Focus the analysis specifically on U.S.-headquartered companies

---

## 📥 Data Source

The original data was scraped from [Wikipedia’s list of S\&P 500 companies](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies), which includes all current constituents along with information such as their ticker symbols, sectors, and headquarters.

---

## 🧹 Data Cleaning & Transformation

To make the dataset analysis-ready, I performed the following key operations:

* **Column Pruning:** Removed non-essential columns that were not relevant to the analysis.
* **Custom Columns:** Created new insights through:

  * **Create from Example**
  * **Custom Columns**
  * **Conditional Columns**
* **String Processing:**

  * Split columns by delimiter
  * Trimmed whitespace
  * Standardized text casing (e.g., all uppercase/lowercase)
* **Filtering Logic:** Isolated companies **headquartered in the U.S.**, removing all others.

This refined dataset now reflects a clean and analysis-ready snapshot of American corporations in the S\&P 500 index.

---

## Why Focus on U.S.-Based Companies?

The S\&P 500 is often seen as a benchmark for the **U.S. economy**, but not all listed companies are headquartered domestically. This project aims to present a **purely U.S.-centric** view of the index, which can be particularly valuable for:

* Domestic policy analysis
* U.S.-focused economic forecasting
* Investment strategies emphasizing home-country bias

---

## 📁 Files

* `S&P 500 American HQ.xlsx` — The cleaned and transformed dataset (included in this repository)

---

## 🔧 Tools Used

* Microsoft Excel / Power Query for data wrangling
* Tableau for data visualization
* GitHub for version control and sharing

---

## 🚀 Next Steps

* 📈 Add data visualizations (e.g., HQ distribution by state, sector breakdown)
* 🔁 Automate data refresh with web scraping or API
* 🧠 Perform deeper statistical analysis or machine learning
