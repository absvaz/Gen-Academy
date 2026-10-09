# Campaign performance dashboard

Open `index.html` in a browser to use the dashboard. It starts with the 16-row **Campaign Data** worksheet from the supplied `campaigns.xlsx`; the normalized copy is `campaigns.csv`. The workbook notes that its values are made-up practice data.

The dashboard includes Overview, Platform Comparison, Campaign Details, and Time Series views. Date, channel, audience, and campaign goal filters are global. Use **Import CSV** to replace the active dataset. Required columns are `Date`, `Campaign`, `Channel` (or `Platform`), `Audience`, `Goal`, `Spend`, `Clicks`, `Conversions`, and `Revenue`. `Impressions` is optional; ROI is always recalculated as `(revenue - spend) / spend` from the filtered totals.

All monetary amounts are shown in USD. The Campaign Details view includes record-level ROI; summary ROI is calculated from summed revenue and spend to avoid averaging campaign percentages.
