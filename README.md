# CSGO-Skinomics 🔫

##  Project Overview
This project performs an **econometric study** of the AK-47 digital asset market within the Counter-Strike ecosystem. Instead of a simple time-series, this analysis focuses on **Market Efficiency** and **Liquidity Spreads** by comparing current asking prices against actual realized transaction values.

## Key Research Objectives
* **Market Spread Analysis:** Measuring the gap between `lowest price` (Ask) and `last sold price` (Bid) to determine asset liquidity.
* **Hedonic Pricing Models:** Quantifying the premium paid for specific attributes such as `StatTrak™` and `Souvenir` technology.
* **Anomaly Detection:** Identifying market outliers where realized prices deviate significantly from current supply, a common technique in **Anti-Money Laundering (AML)** and fraud detection.
* **Arbitrage Identification:** Spotting price discrepancies that suggest market inefficiency or "sniping" opportunities.

##  Tech Stack
* **SQL (Advanced):** Using Common Table Expressions (CTEs) and Window Functions to rank assets by liquidity.
* **Python:** For data cleaning and visualizing price distribution density.
* **Microeconomics:** Applying concepts of **Bid-Ask Spread** and **Price Discovery**.

##  Current Status
* [x] Data sourcing: AK-47 Market Snapshot (Kaggle).
* [ ] Data cleaning: Removing outliers and non-representative listings.
* [ ] Spread & Liquidity calculation using SQL.
* [ ] Final report on Market Efficiency.

---
*Created by [Javier Carrasco Díaz] - Economics & Data Analytics Student*
