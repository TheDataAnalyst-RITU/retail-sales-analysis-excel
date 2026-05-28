# 🛍️ Vrinda Store – Annual Sales Analysis (2022)

An end-to-end data analytics project built entirely in **Microsoft Excel**, covering the full workflow from raw, messy data all the way to an interactive dashboard with business recommendations.

This project takes a real-world style retail dataset (~31,000 order records) and turns it into a clean, decision-ready **annual sales report** — the kind a business owner could actually use to plan for next year.

---

## 🎯 Objective

Vrinda Store wanted to create an **Annual Sales Report for 2022** so the business could clearly understand its customers and find ways to **grow sales in 2023**.

The goal was simple but practical: take a year's worth of order data, make sense of it, and answer the questions that actually matter to the business.

---

## ❓ Questions This Project Answers

These were the key business questions I set out to answer:

- Compare the **sales and orders** trend using a single chart
- Which **month** had the highest sales and orders?
- Who purchased more in 2022 — **men or women**?
- What were the different **order statuses** (delivered, returned, cancelled, refunded)?
- What are the **top 10 states** contributing to sales?
- What is the **relationship between age and gender** based on number of orders?
- Which **sales channel** contributes the most to overall sales?
- What is the **highest-selling category**?

---

## 🗂️ About the Dataset

The dataset contains around **31,000 rows** of order-level data from 2022. Each record represents a single order and includes fields like:

| Field | Description |
|-------|-------------|
| Order ID | Unique identifier for each order |
| Cust ID | Customer identifier |
| Gender, Age | Customer demographics |
| Date | Order date |
| Status | Delivered, Returned, Cancelled, Refunded |
| Channel | Amazon, Myntra, Flipkart, Ajio, etc. |
| Category | Set, Kurta, Western Dress, Top, Saree, etc. |
| Size, Qty, Amount | Order details |
| Ship City / State / Postal Code | Shipping location |
| B2B | Business vs. individual customer flag |

---

## 🧹 1. Data Cleaning

Before any analysis, the raw data needed tidying up. This is the unglamorous but most important step — clean data is what makes everything after it trustworthy.

Here's what I did:

- **Removed blanks and irrelevant columns** that didn't add value to the analysis
- **Fixed inconsistent text** (extra spaces, mismatched casing) so values grouped correctly in pivots
- **Standardized data types** — making sure dates were read as dates, amounts as numbers, etc.
- **Checked for duplicates** to avoid double-counting orders
- **Validated categories** like Gender, Status, and Channel so they were consistent throughout

> 💡 *Excel skills used:* `TRIM`, `Find & Replace`, removing duplicates, filtering, and formatting cells to correct data types.

---

## ⚙️ 2. Data Processing

With clean data in place, I created a few new columns to make the analysis easier and richer — this is **feature engineering** done the Excel way.

- Created an **Age Group** column (Teenager / Adult / Senior) so I could analyze buying behaviour by life stage
- Extracted the **Month** from the order date to enable month-over-month trend analysis
- Set up helper columns so the pivot tables could slice the data exactly how I needed

> 💡 *Excel skills used:* `IF` / nested `IF`, `MONTH()`, `TEXT()`, and building helper columns.

---

## 📊 3. Data Analysis

This is where the data started telling a story. I used **PivotTables** to summarize and explore the data from different angles — by month, gender, age group, state, channel, and order status.

PivotTables made it easy to ask a question, drag a few fields, and get an instant answer — then dig deeper from there.

> 💡 *Excel skills used:* PivotTables, grouping, sorting, value summarization (Sum, Count), and % of total calculations.

---

## 📈 4. Data Visualization

Numbers in a table are fine, but charts make the story obvious. For each PivotTable I built a matching **PivotChart** to make the insights easy to read at a glance:

- 📉 **Line + Column combo chart** → Orders vs. Sales across months
- 🥧 **Pie charts** → Men vs. Women sales, and Order Status breakdown
- 📊 **Bar chart** → Top 10 states by sales
- 📊 **Clustered column chart** → Orders by Age Group and Gender
- 🥧 **Pie chart** → Sales by Channel

> 💡 *Excel skills used:* PivotCharts, combo charts, formatting axes and labels, and choosing the right chart for each question.

---

## 🖥️ 5. Interactive Dashboard (The Final Report)

All the charts came together into a single, clean **interactive dashboard** — the actual deliverable Vrinda Store would use.

What makes it interactive:

- **Slicers** for **Month**, **Category**, and **Channel** let the user filter the entire dashboard with one click
- Every chart updates instantly when a slicer is selected
- A consistent layout and colour theme so it reads like a finished business report, not a spreadsheet

💡 *Excel skills used:* Slicers, dashboard layout design, connecting slicers to multiple PivotCharts, and visual formatting.

---

## 🔍 6. Key Insights

Here's what the 2022 data revealed:

- 👩 **Women drove the majority of sales** — about **64%** of purchases came from women vs. 36% from men.
- 📅 **March was the peak month** for both sales and orders, with a clear slowdown toward the end of the year.
- 📦 **Most orders were fulfilled successfully** — around **92% delivered**, with returns, cancellations, and refunds making up the rest.
- 🗺️ **Maharashtra, Karnataka, and Uttar Pradesh** were the **top contributing states** to overall sales.
- 🧑‍🤝‍🧑 **Adult women** were the single biggest customer segment by order volume, followed by teenagers.
- 🛒 **Amazon, Myntra, and Flipkart** together brought in the **majority of orders**, with Amazon leading the way.
- 👗 **"Set" and "Kurta"** were the **top-selling categories** by far.

---

## 💡 7. Recommendations & Next Steps

Based on the insights, here's what Vrinda Store could do to grow in 2023:

- **Lean into the core customer.** Adult women are the biggest segment — tailor marketing, product range, and offers toward them.
- **Plan inventory around demand.** Stock up on "Set" and "Kurta" categories, which clearly dominate sales.
- **Double down on top channels.** Amazon, Myntra, and Flipkart drive most orders — strengthen presence and promotions there.
- **Boost the slower months.** Sales dipped in the second half of the year; targeted campaigns or seasonal offers could smooth that out.
- **Prioritize top states.** Faster shipping, regional promotions, or local campaigns in Maharashtra, Karnataka, and UP could lift returns even further.

---

## 🛠️ Tools & Skills

- **Microsoft Excel** — the only tool used, start to finish
- Data Cleaning & Data Processing
- PivotTables & PivotCharts
- Slicers & Interactive Dashboards
- Data Visualization & Reporting
- Translating data into business recommendations

---

## 📝 A Note on This Project

This project began as a guided learning exercise to strengthen my Excel and analytics fundamentals — and I've documented the full workflow here in my own words to show how I approach a real analysis: clean it, process it, explore it, visualize it, and turn it into recommendations a business can actually act on.

---
  
## 📌 *Dashboard screenshot:*

![Vrinda Store Dashboard](https://github.com/TheDataAnalyst-RITU/Excel-Project---Vrinda-Store-Sales-Analysis/blob/main/Vrinda%20Store%20Sales%20Anaysis%20Dashboard.png)
