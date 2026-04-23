# 📤 Shopee API: Submit Product Detail Task

This endpoint is the entry point for retrieving deep product intelligence. Our system uses an **asynchronous workflow** to ensure that high-volume data requests are processed with maximum stability and success rates.

### 📝 Overview
The **Submit Task** endpoint allows you to register a specific Shopee product for data extraction. Instead of waiting for a slow direct response, the system accepts the task and provides you with a tracking ID.

### 🔄 How it Works:
1. **Request:** You provide the `shop_id`, `item_id`, and the target `country`.
2. **Acceptance:** The API validates your request and returns a `batch_id`.
3. **Queueing:** Our high-speed crawlers process the task in the background.

### 🔑 Authentication & Parameters
To ensure security and accurate billing, all submission requests require:
* **X-API Credentials:** Secure tokens for identity and rate-limiting.
* **Target Identifiers:** Specific Shopee IDs and Site Codes (e.g., PH, MY, TW).

---

### 📖 Full Technical Specification
To view the complete API reference, including **Request Headers, Query Parameters, and cURL Examples**, please visit our official documentation portal:

👉 [**Technical Docs: Submit Product Detail Task**](https://bodapi.com/en/apis/shopee-api/submit-product-detail)

---
### 📞 Business Inquiry (Bodapi Technical Team)

* **Official Website:** [https://bodapi.com](https://bodapi.com)
* **WeChat (微信):** daniellehallasgo
* **Telegram:** [@bodapi_dan](https://t.me/bodapi_dan)
* **Email:** support@bodapi.com

*Maintained by Bodapi - 2026 Technical Operations Team*
