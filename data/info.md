# 🧾 Dataset Information: E-commerce Events – Cosmetics Shop

**Source:**  
📌 [Kaggle – Ecommerce Events History in Cosmetics Shop](https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-cosmetics-shop)

---

## 📦 Dataset Description

This dataset simulates user interactions from a multi-category online cosmetics store. It contains over **4 million records** of customer behavior over a one-month period, including events such as:

- Product views
- Add to cart
- Remove from cart
- Purchases

---

## 📁 File Format

- **Type:** CSV files (split by day, e.g., `2019-Nov.csv`)
- **Size:** ~15 GB total
- **Structure:** Tabular

---

## 🔑 Key Columns

| Column Name     | Description                                       |
|------------------|---------------------------------------------------|
| `event_time`     | Timestamp of the customer action                 |
| `event_type`     | Type of event: `view`, `cart`, `remove_from_cart`, `purchase` |
| `product_id`     | Unique ID of the product                         |
| `category_id`    | Product category ID                              |
| `category_code`  | Product category in code format                  |
| `brand`          | Product brand (where available)                  |
| `price`          | Price at the time of event                       |
| `user_id`        | Unique ID representing the user                  |
| `user_session`   | User’s browsing session                          |

---

## 🎯 Usage in This Project

This dataset is used to:

- Analyze customer journey behavior across touchpoints
- Perform **Funnel Analysis** to evaluate conversion drop-offs
- Apply **RFM Segmentation** to categorize customers by value
- Simulate a real-world customer insights freelance scenario

---

## 🛡️ Note

This dataset is publicly available and used here for **portfolio and learning purposes only**. All analysis, insights, and visualizations are custom-built and do not represent actual client data.
