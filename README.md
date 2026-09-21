# BlinkIT Grocery Analytics: Sales Performance & Outlet Insights

An exploratory data analysis of **8,523 grocery item records** using SQL to understand sales performance across product categories, pricing ranges, outlet characteristics, and location tiers.

The analysis looks at product sales, fat content, item categories, outlet size, location tiers, outlet types, and price ranges. The goal is to turn grocery sales data into simple insights that can support business and outlet-level decisions.

**Total Sales:** 18.59M | **Total Items:** 8,523 | **Average Sales/Item:** 2,180.79

## Data Preparation

Before the analysis, the dataset was checked and prepared using SQL.

The main steps included:

* Checking the total number of records
* Checking missing values in key columns
* Standardising inconsistent `Item_Fat_Content` values such as `LF`, `low fat`, and `reg`
* Handling missing values in relevant columns
* Creating price ranges based on `Item_MRP`
* Aggregating sales across product categories, outlet characteristics, and locations

The analysis contains **8,523 grocery item records** across different product and outlet categories.

## Key Findings & Business Insights

### 1. Sales Performance by Product Category

**Fruits and Vegetables** generated the highest total sales among item categories, with approximately **2.82M**, followed by **Snack Foods (2.73M)** and **Household (2.06M)**.

These categories contribute a relatively large share of total sales compared with other product categories in the dataset.

**Business takeaway:** Product-level sales analysis can help identify categories that contribute more to overall revenue and may require closer attention when reviewing product performance.

---

### 2. Sales Performance by Fat Content

After standardising inconsistent labels such as `LF`, `low fat`, and `reg`, **Low Fat** products generated approximately **11.90M in total sales**, while Regular products generated approximately **6.68M**.

This shows that Low Fat products account for a larger share of sales within the dataset.

**Business takeaway:** Fat-content categories can be used as one factor when reviewing product performance and understanding differences in sales across product attributes.

---

### 3. Sales Performance by Outlet Size

**Medium-sized outlets** generated the highest total sales at approximately **7.49M**, followed by Small outlets (**4.57M**) and High outlets (**2.14M**).

Medium outlets also recorded the highest average sales per item at approximately **2,682**.

**Business takeaway:** Comparing total and average sales across outlet sizes can help businesses understand how different outlet formats contribute to sales performance.

---

### 4. Sales Performance by Location Tier

**Tier 3 locations** generated the highest total sales at approximately **7.64M**, followed by Tier 2 (**6.47M**) and Tier 1 (**4.48M**).

However, **Tier 2** recorded the highest average sales per item at approximately **2,323**, compared with **2,279** for Tier 3.

This shows that total sales and average sales per item can provide different perspectives when comparing location performance.

**Business takeaway:** Location-level analysis can help distinguish markets with higher overall sales from markets with higher average sales per item.

---

### 5. Sales Performance by Outlet Type

**Supermarket Type1** generated the highest total sales in the dataset at approximately **12.91M**, followed by Supermarket Type3 (**3.45M**) and Supermarket Type2 (**1.85M**).

However, **Supermarket Type3** recorded the highest average sales per item at approximately **3,694**.

This highlights the difference between overall sales contribution and average sales performance.

**Business takeaway:** Looking at both total sales and average sales can provide a more complete view of outlet performance.

---

### 6. Sales Performance by Price Range

The **Premium (100–200)** price range generated the highest total sales at approximately **10.74M**, followed by **Luxury (200+)** products at **5.26M**.

The Premium range also contains the largest number of items in the dataset, with **4,597 records**.

**Business takeaway:** Price-range analysis can help businesses understand which product price segments contribute more to overall sales and provide an initial reference for product and pricing analysis.

## Business Recommendations

Based on the analysis:

* **Product Categories:** Monitor high-performing categories such as Fruits and Vegetables and Snack Foods when reviewing product performance.
* **Outlet Strategy:** Compare sales across outlet sizes and types to understand which formats contribute more to total and average sales.
* **Location Analysis:** Consider both total sales and average sales when comparing performance across location tiers.
* **Pricing Analysis:** Use price-range performance as an initial reference when evaluating product mix and pricing segments.

## Tools Used

* **SQL** — Data cleaning, standardisation, filtering, aggregation, and analysis
* **Excel** — Data checking and supporting analysis
* **Exploratory Data Analysis (EDA)** — Identifying patterns, trends, and differences across products and outlets
* **Business Analysis** — Translating sales findings into practical business insights

## Dataset

The dataset used in this project is publicly available on Kaggle:

**Source:** [BlinkIT Grocery Dataset](https://www.kaggle.com/datasets/mukeshgadri/blinkit-dataset)
