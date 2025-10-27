# CLV-CAC-Analysis-for-Case-Study-UCL
Marketing analytics case study for a bubble tea startup, including customer segmentation, CAC, CLV, and loyalty program analysis using R and Quarto.

# Marketing Analytics Case Study: CLV & CAC Analysis 📈

![Language](https://img.shields.io/badge/Language-R-blue.svg)
![Tool](https://img.shields.io/badge/Tool-Quarto-purple.svg)
![Status](https://img.shields.io/badge/Status-Completed-green.svg)

## Project Overview

This repository contains a comprehensive marketing analytics case study for a new bubble tea startup in Canary Wharf, London. The project applies data-driven techniques to inform key marketing strategy decisions, including customer acquisition, segmentation, and retention.

The analysis was performed using **R** within a **Quarto** document and covers:
- A 5C situation analysis of the market.
- Calculation of Customer Acquisition Costs (CAC) for different channels.
- Customer segmentation based on survey data.
- Calculation of Customer Lifetime Value (CLV) to identify high-value segments.
- A financial evaluation of a proposed customer loyalty program.

---

## Key Findings & Recommendations 💡

### 1. Customer Segmentation Reveals Two Key Groups

Analysis of survey data identified two distinct customer segments:

* **"Foodies"**: A highly valuable segment that purchases twice as frequently, spends 50% more per transaction, and has a much higher retention rate (85% vs 70%).
* **"Non-Foodies"**: A more casual and less predictable customer base.

### 2. Acquisition Costs Vary Dramatically by Channel

The cost to acquire a single customer was calculated for three methods:

* **Search Engine Marketing (SEM)**: **£2.00**
* **Targeted Mailing**: **£24.00**
* **Blanket Mailing**: **£30.00**

**Recommendation**: Prioritize SEM as the primary, long-term acquisition channel due to its exceptional cost-efficiency. Use blanket mailing only for initial launch awareness.

### 3. Customer Lifetime Value (CLV) Confirms "Foodies" are the Priority

CLV calculations over a 2-year period highlight a massive difference in segment value:

* **Foodie CLV**: **£162.65**
* **Non-Foodie CLV**: **£26.94**

**Recommendation**: "Foodie" customers are profitable to acquire through any channel, justifying higher marketing spend to attract them. "Non-foodies" are only profitable if acquired via low-cost channels like SEM.

### 4. Loyalty Program Is a Clear Financial Win

A proposed loyalty program was projected to deliver a total profit increase of **£11,437.17**.

* The program increases the CLV of each "Foodie" by **+£32.46**.
* This gain significantly outweighs the minor loss of **-£1.78** per "Non-Foodie" customer.

**Recommendation**: The loyalty program should be implemented, as it is a highly effective tool for retaining the most valuable customer segment.

---

## Repository Contents

* **`Assignment 1 Answer Sheet.qmd`**: The Quarto source file containing all R code, analysis, and commentary.
* **`survey_data.csv`**: The raw survey data used for the quantitative analysis.
* **`MSIN0094-assignment1-VVMQ9.pdf`**: The final, rendered report submitted for the assignment.
