# Global Electronics Retailer – Sales & Profitability Analysis

## Dashboard Preview

![Global Electronics Dashboard](dashboard.png)

Created an end-to-end Excel analytics project that is exploring sales, profitability, customer purchasing behaviour and delivery performance for a global electronics retailer. The objective is to identify where growth and risk are concentrated across products, markets and sales channels.

## Project overview

-Data source: Maven Analytics – Global Electronics Retailer (public portfolio dataset).
-Period: January 2016 – February 2021 (2021 is partial).
-Dataset: 62,884 sales line items across 26,326 orders.
-Tools: Microsoft Excel, Power Query, PivotTables, PivotCharts, Excel formulas, slicers and timeline filters.

## Business questions

1. How have sales and profitability changed over time?
2. Which product categories and individual products drive revenue?
3. Which geographical markets contribute the most to sales and profit?
4. How has the online channel performed relative to in-store sales?
5. How has online delivery performance changed over time?
6. What do repeat purchasing and customer revenue concentration reveal?

## Data preparation and analysis

1. I used Power Query to clean and merge the Sales, Products, Stores and Exchange Rates data.
2. Prepared a consolidated sales analysis table containing order, product, store, currency and delivery information.
3. Included derived analytical fields for sales amount (USD), cost (USD), profit (USD), profit margin, sales channel, delivery status and delivery days.
4. Used PivotTables to summarise sales, profit, quantity, annual trends, product performance, country/channel performance and delivery status.
5. Built an interactive Excel dashboard with KPI cards, PivotCharts, country and category slicers, and an order-date timeline.

## Dashboard

Open the Excel workbook and navigate to the 'DASHBOARD' worksheet. Use the country and category slicers and the order-date timeline to filter the dashboard. The 'ABOUT' worksheet documents the project scope and limitations.

## KPI's

| Metric | Result |
| --- | ---: |
| Total sales | $55,755,479.59 |
| Total gross profit | $32,662,688.38 |
| Gross profit margin | 58.58% |
| Units sold | 197,757 |
| Total orders | 26,326 |
| Sales line items | 62,884 |

## Key findings

### 1. Overall performance

- The retailer generated $55.8 million in sales and $32.7 million in gross profit, with a gross margin of approximately 58.6%.
- The workbook documents broadly stable margins across countries and categories. Revenue volume and product mix are therefore useful areas to investigate when explaining differences in profit; the analysis does not isolate the effect of pricing.

### 2. Growth and risk

- Annual sales increased each year from 2016 through 2019, reaching $18.3 million in 2019, approximately 43% higher than in 2018.
- Sales declined by approximately 49% in 2020 compared with 2019, with the dashboard documenting the start of the decline in March 2020.
- The 2021 figures cover only January and February and should not be compared directly with full-year totals.

| Year | Sales (USD) |
| --- | --: |
| 2016 | $6.95M |
| 2017 | $7.42M |
| 2018 | $12.79M |
| 2019 | $18.26M |
| 2020 | $9.29M |
| 2021 (Jan–Feb) | $1.04M |

### 3. Product mix

- Computers generated $19.30 million in sales (approximately 35%), followed by Home Appliances at $10.80 million (approximately 19%). Together, they accounted for 54% of revenue.
- All five highest-revenue products were desktop PCs.
- Games and Toys was the smallest category, accounting for approximately 1.3% of sales, and recorded the lowest gross margin (54.7%). It is a candidate for further review.

### 4. Countries and sales channels

- The United States was the largest geographical market, generating $23.76 million (approximately 43% of total sales).
- Online sales reached $11.40 million (20.5% of total sales), exceeding sales in the United Kingdom alone.
- The dashboard documents an increasing online revenue share: 16.8% in 2016, 22.3% in 2020 and 27.5% in January–February 2021.
- France was the smallest geographical market ($1.23 million), but the dashboard identifies it as the fastest-growing market in 2019 (+70%) and the most resilient in the 2020 downturn (-32%, compared with declines of 47–59% elsewhere).

### 5. Online delivery performance

- Average delivery time improved from 7.3 days in 2016 to approximately four days from 2019 onward.
- The share of online orders taking seven or more days to arrive fell from 61% in 2016 to 9% from 2019 onward.
- Average delivery times were broadly consistent across product categories, ranging from 4.4 to 4.9 days.

### 6. Customer purchasing behaviour

- 61% of customers placed more than one order.
- The top 10% of customers accounted for 36% of total sales, indicating revenue concentration among a relatively small group of customers.

## Business recommendations

The following are suggested actions based on the documented findings, rather than measured outcomes:

- Prioritise inventory availability and monitor demand in Computers and Home Appliances, while assessing the risk of dependence on these categories.
- Review the Games and Toys assortment and profitability before making decisions about reducing or expanding it.
- Investigate the drivers of the online channel's growing sales share and maintain delivery performance as the channel develops.
- Examine France's relative resilience to identify potentially transferable market practices.
- Monitor repeat purchasing and customer concentration, and explore retention initiatives without relying excessively on high-value customers.
- Investigate the causes of the 2020 sales decline using additional market and operational data.

## Limitations

- 2021 contains only January and February data.
- Online is a sales channel, not a geographical country; it must be interpreted separately in country comparisons.
- The dataset does not contain promised delivery dates, returns or complaints, so delivery duration can be measured but on-time delivery rates and service failures cannot be assessed.
- The analysis is descriptive and does not establish causal relationships.

## Repository contents

The Excel workbook contains the prepared sales analysis table, supporting PivotTables, dashboard and project documentation. The workbook is the primary project deliverable.

