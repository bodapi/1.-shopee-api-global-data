# 🔍 Guide: Querying Product Detail Task Results

After submitting a crawl task, the next step is to retrieve the data. Since our system processes requests asynchronously to ensure high success rates, you need to **Query** the status of your task.

### 📝 Overview
The **Query Task** endpoint is used for polling. It checks whether the Shopee data you requested has been successfully crawled and is ready for download. Once the task is complete, the API delivers the full, structured product payload.

### 🔄 The Polling Process:
1. **Submit:** You receive a `batch_id` from the initial submission.
2. **Poll:** You call the Query endpoint using the same identifiers (`shop_id`, `item_id`, `country`).
3. **Status Check:** * If the system is still working, it will return a "Processing" status.
   * If the crawl is finished, it returns the complete data object.

### 📊 What’s Inside the Result?
Once a task is marked as successful, the system provides comprehensive data points, including:
* **Item Specifications:** Full titles, currency, and attributes.
* **Shop Insights:** Detailed seller information and ratings.
* **Real-time Metadata:** Timestamps of exactly when the data was crawled.

---

### 📖 Full Technical Specification
For the complete list of **HTTP Status Codes, Response Fields (JSON Structure), and cURL Examples**, please refer to our official documentation:

👉 [**Technical Docs: Query Product Detail Task Result**](https://bodapi.com/en/apis/shopee-api/query-product-detail)

---
### 📞 Business Inquiry (Bodapi Technical Team)

* **Official Website:** [https://bodapi.com](https://bodapi.com)
* **WeChat (微信):** daniellehallasgo
* **Telegram:** [@bodapi_dan](https://t.me/bodapi_dan)
* **Email:** support@bodapi.com

*Maintained by Bodapi - 2026 Technical Operations Team*
