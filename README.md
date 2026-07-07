---

## Data Source

This project uses the publicly available **Instacart Online Grocery Basket Analysis Dataset**, originally released for the Instacart Market Basket Analysis competition and available on Kaggle.

**Dataset:**
 [oai_citation:0‡kaggle.com](https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset?utm_source=chatgpt.com)

The dataset contains over **3 million grocery orders** from more than **200,000 anonymized users**, including purchase history, product information, and relative time between orders. It provides a valuable foundation for studying customer purchasing behavior and shopping patterns.  [oai_citation:1‡Kaggle](https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset?utm_source=chatgpt.com)

---

## Data Limitations

As a public competition dataset, several business-critical metrics are intentionally unavailable, including:

- Product prices and revenue
- Customer lifetime value (LTV)
- Marketing exposure and promotions
- Session-level behavioral events
- Long-term retention and business outcomes

Because these metrics cannot be directly measured, this project develops a behavioral growth framework using **Weekly Active Items (WAI)** as a proxy for customer engagement. The objective is not to estimate actual business performance, but to identify scalable behavioral growth opportunities under the constraints of the available data.
