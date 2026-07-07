# Behavioral Growth Strategy for Instacart Marketplace

> **A strategy case study integrating behavioral analytics, product thinking, and quantitative modeling to identify scalable marketplace growth opportunities.**

---

## Executive Summary

This project investigates how customer behavior influences marketplace growth using the Instacart Online Grocery Shopping Dataset.

Rather than focusing on individual transactions, the analysis examines behavioral transitions across engagement levels to identify scalable growth opportunities. The findings are translated into a structured growth strategy and supported by quantitative impact modeling.


## Data Source

This project uses the publicly available **Instacart Online Grocery Basket Analysis Dataset**, originally released for the **2018 Instacart Market Basket Analysis** competition and available on Kaggle.

**Dataset:** [Instacart Online Grocery Basket Analysis Dataset (Kaggle)](https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset)

The dataset represents a selected sample of Instacart users from the 2018 competition and does not include geographic, demographic, or other customer profile information. Findings should therefore be interpreted as **directional behavioral insights for this user cohort**, rather than a representation of current platform performance or the overall Instacart user base.

---

## Data Limitations & Disclaimers

### Data Limitations

As a public competition dataset, several business-critical metrics are intentionally unavailable, including:

- Product prices and revenue
- Customer lifetime value (LTV)
- GMV and wallet share
- Marketing exposure and promotions
- Session-level behavioral events
- Absolute order timestamps
- Long-term retention outcomes

Because these metrics cannot be directly measured, this project develops **Weekly Active Items (WAI)** as a behavioral proxy for customer engagement and marketplace growth analysis.

### Quantification Disclaimer

The growth impact estimates presented in this project are modeled projections assuming predefined behavioral improvements (e.g., **+1–3 unique items per order** or **3–10 percentage point reductions in 10+ day purchase gaps**) are achieved.

These estimates are intended to compare the relative potential of different growth levers rather than predict actual business performance. Actual impact depends on the effectiveness of product interventions and should be validated through experimentation (e.g., A/B testing).
