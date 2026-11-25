# Supermarket Sales Analysis — Portfolio Practice Project

**By:** Muhammad K. — Data Analyst in progress, Madinah, Saudi Arabia
**GitHub:** https://github.com/km038805-ui
**Skills used:** Excel, Google Sheets, Python, Pandas, Data Cleaning, Data Analysis

> Portfolio practice project. This is **not client work and not work for any employer**.
> The data is public Kaggle data, analysed as practice.

## Data source
- **Kaggle dataset:** Supermarket Sales — https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales
- **File:** `supermarket_sales.csv` — 1,000 rows, 17 columns, sales from 3 branches in Myanmar (Yangon, Mandalay, Naypyitaw), Jan–Mar 2019.
- **Download mirror used (no Kaggle login needed):** https://github.com/vikramnayyar/Supermarket-Sales-Analysis (data/data.csv)
- **Licence / use:** public Kaggle dataset, free for educational and analytical use.

## What I cleaned
- Standardised column names to snake_case (e.g. `Invoice ID` -> `invoice_id`).
- Converted `date` to a real date and added a `month` column.
- Checked for duplicate invoice IDs: **0 removed**.
- Missing values after cleaning: **0**.
- Saved the cleaned file as `supermarket_sales_cleaned.csv` and `supermarket_sales_cleaned.xlsx` (with summary sheets).

## Key findings (real numbers from the data)
- Total sales: **$322,966.75** across 1000 transactions.
- Total gross income: **$15,379.37**.
- Average transaction: **$322.97**; average customer rating **6.97/10**.
- Best branch: **Branch C** — $110,568.71; Branch A $106,200.37, Branch B $106,197.67.
- Top product line: **Food and beverages** — $56,144.84.
- Sales by payment: Cash $112,206.57, Ewallet $109,993.11, Credit card $100,767.07.
- Members spent slightly more than normal customers: $164,223.44 vs $158,743.30.
- Monthly sales: Jan 2019 $116,291.87, Feb $97,219.37, Mar $109,455.51 — January was the strongest month.

## Files
- `supermarket_sales_cleaned.csv` / `.xlsx` — cleaned data + Excel summaries
- `analysis.py` — Python/Pandas cleaning and analysis (run `python3 analysis.py`)
- `charts/` — sales by product line, by branch, by payment method
- `findings.json` — all numbers above, computed by the script

Note: The cleaned Excel workbook (.xlsx) and chart images are in the local portfolio / CV, not in this repo, because this upload contains text files only.

## What a business can learn from this
Food and beverages is the top-selling line, Branch C leads slightly, and cash is still the most used payment method — so stock and staffing should favour food and beverages, and the Branch C layout is worth copying.
