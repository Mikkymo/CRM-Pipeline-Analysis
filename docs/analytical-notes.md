# Analytical Notes

[Back to project overview](../README.md)

## Objective

How much revenue has been won, how are opportunities progressing, and which accounts require closer attention?

## Data and method

Connect opportunities with accounts, products, and sales teams. Check relationship keys and unmatched records before interpreting segments. Define won revenue separately from open pipeline value and compare deal stages and sales-cycle patterns.

## Reported results and definitions

| Metric | Result |
| --- | ---: |
| Opportunity records | 8,800 |
| Won revenue | $10,005,534 |
| Won opportunities | 4,238 |
| Lost opportunities | 2,473 |
| Closed-deal win rate | 63.1% |
| Open opportunities | 2,089 |

The closed-deal win rate is won ÷ (won + lost). Open opportunities are excluded because their outcomes are not yet known.

## Review the analysis

Open `powerBI_final.pbix` in Power BI Desktop. Review the four CSV files and data dictionary alongside the data-model screenshot. If source-file locations differ on your machine, update them before refreshing.

## Interpretation

- Review the age, stage, and potential value of open opportunities before prioritising follow-up.
- Investigate account concentration and differences in sales-cycle duration.
- Use consistent KPI definitions when comparing sales teams or segments.

## Limitations

The dataset represents a fictitious company. Won revenue is historical revenue, not open pipeline value. Open status alone does not establish that a deal is stalled, and the project does not demonstrate realised revenue or forecasting improvements.

## Historical material

Earlier reports and presentations remain in the archive as historical deliverables. They have not been rewritten or independently reconciled in this documentation cleanup. Use the current project overview for the stated findings and definitions.

## Source and table coverage

[Maven Analytics CRM Sales Opportunities](https://mavenanalytics.io/data-playground/crm-sales-opportunities): 8,800 opportunities, 85 accounts, 35 sales-team records, and 7 products. Field descriptions are in [the data dictionary](../data_dictionary.csv).
