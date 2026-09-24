# Golden Wok: Delivery Performance and Data Quality

This Power BI project analyzes Golden Wok food delivery performance across 5,000 orders, focusing on delivery performance, profitability, customer experience, and data quality. The report highlights business results while clearly separating valid analytical records from source-data issues in delivery time, food temperature, and SLA coverage.

## Tools

- Power BI
- CSV source data

## Key Metrics

- Orders: 5,000
- Order value: NGN 380.6M
- Delivery cost: NGN 30.5M
- Supplied profit: NGN 2.49M
- Valid delivery-time observations: 1,149
- Valid temperature observations: 314
- SLA coverage: 84 eligible orders, with 12 compliant and 72 breached

## Files

- `jongoGW.pbix` - final Power BI report
- `GW.pdf` - exported report PDF
- `out/control_tower.png` - dashboard image used for the submission post
- `data/` - source CSV files used in the report

## Note

The dashboard keeps data-quality limitations visible. Delivery-time, temperature, and SLA metrics use screened records so the conclusions are based on valid observations rather than implausible source values.
