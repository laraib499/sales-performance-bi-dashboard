# Sales Performance & Business Intelligence Dashboard

An interactive **Microsoft Power BI** dashboard project exploring retail sales, profitability, budget performance, customer behaviour, product categories and time-based trends.

**Author:** Laraib Farhan  
**Platform:** Microsoft Power BI Desktop  
**Dataset period shown:** 2022–2024  
**Business context:** ABC Retail

## Project overview

This report turns retail sales data into an interactive business intelligence experience. It includes six analytical areas:

1. **Sales Analysis** — KPI cards, regional and monthly sales, yearly sales, category and sub-category analysis, and top-five products.
2. **Actual vs Budget Analysis** — actual sales compared with target, monthly differences, regional/category comparisons and city-level mapping.
3. **Trend Analysis** — orders and customers by year, sales versus target, sub-category trends, top customers by sales/profit, and daily sales forecast.
4. **Detailed Sales Analysis** — monthly sales, cash-flow visual, KPI card, selectable sales/time-intelligence measures and a detailed date-level table.
5. **AI Visual – KPI / Key Influencers** — explores factors associated with increases in average sales.
6. **Decomposition Tree** — interactive drill-down of sales by category, sub-category, region, segment, year and ship mode.

## Dashboard highlights

The supplied PDF export displays these headline values:

| KPI | Displayed value |
|---|---:|
| Sales | $112.878282M |
| Average Sales | 16.86K |
| Quantity | 502K |
| Order Returns | 1K |
| Total Customers | 782 |
| Sum of Cost | 1M |
| Profit | 79.95M |
| Expense | 75M |
| Total Orders | 7K |
| Target | $71.083497M |

The Actual vs Budget page shows total sales of **$112,878,282**, target of **$71,083,497**, and a displayed difference of **$41,794,785**.

> Figures above are transcribed from the provided report export. They are presented as dashboard outputs, not independently audited business results. Validate measure definitions and calculations in the PBIX before relying on them.

## Interactive features and visuals

- Year, month, date, segment, region and category slicers
- KPI cards and summary measures
- Regional sales, monthly sales and yearly sales charts
- Category and sub-category breakdowns
- Top-five products and top-ten customers
- Actual-versus-target comparison table and charts
- City-level sales map
- Key Influencers AI visual
- Decomposition Tree
- Sales parameter selector and time-intelligence measures
- Cross-filtering across report visuals

## Repository contents

- `dashboard/` — editable Power BI report and exported PDF deliverables
- `docs/` — report page guide and project notes
- `screenshots/` — optional page images for quick portfolio viewing
- `data/` — dataset documentation (do not add restricted source data)
- `dax/` — verified DAX measure documentation

## Open the project

1. Install Microsoft Power BI Desktop.
2. Download the `.pbix` report from `dashboard/`.
3. Open it in Power BI Desktop.
4. If prompted, reconnect the authorized data source.
5. Review the report pages and interact with slicers and drill-down visuals.

## Data and usage notes

The PDF is a static export; use the PBIX for interactive exploration. The source dataset is not included in this repository. Do not publish confidential, personal, customer-identifiable or otherwise restricted data. Confirm source permissions before sharing data or refreshing the model.

## Future enhancements

- Add a concise business-insights section backed by validated measures.
- Document core DAX calculations and Power Query transformations.
- Add clear page screenshots for quick review on GitHub.
- Validate KPI definitions, relationships, forecast assumptions and visual interactions.

Feedback and suggestions are welcome through GitHub Issues.
