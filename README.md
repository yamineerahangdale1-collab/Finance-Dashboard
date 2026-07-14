# Festman Stores – Financial Analysis Dashboard

## Overview

This is a Power BI dashboard built for Festman Stores, a multi-country retail business. The dashboard consolidates sales, profit, discount, and margin data across countries, customer segments, and products, giving a single view of financial performance for the current year against the prior year.

## Problem Statement

Festman Stores operates across multiple countries and sells to different customer segments, from large enterprise accounts to small business buyers, through a network of channel partners. Sales and finance teams needed a way to track performance without pulling separate reports for each country or segment every time. The dashboard was built to answer a few core questions: which markets and segments are driving revenue, where is profit actually being made or lost, how much discounting is eating into margin, and which products are carrying the business.

## Data and Tools

The dataset covers order-level transactions with fields for country, segment, product, discount band, sales amount, profit, and order date. The report was built entirely in Power BI Desktop, using Power Query for data shaping and DAX for year-over-year comparisons and time intelligence measures.

## Key Metrics on the Dashboard

The top row tracks five headline numbers, each compared against the prior year: total sales, total orders, total profit, profit margin, and total discount given. Sales stand at 9.23 crore against 2.64 crore last year, a jump of nearly 249 percent, and orders followed a similar pattern, up around 225 percent to 8.61 lakh. Profit grew even faster in percentage terms, up close to 236 percent to 1.30 crore. The one metric moving in the wrong direction is profit margin, which slipped from 14.7 percent to 14.1 percent, a small but real decline even as absolute profit grew. Discount given also rose sharply alongside sales, up 229 percent to 70.6 lakh.

## Breakdown by Country, Segment, and Product

Orders by country show Canada, France, and the United States as the top three markets by order volume, with Mexico and Germany close behind. Profit margin by country tells a different story. Germany leads at 15.66 percent, followed by France and Canada, while Mexico and the United States sit at the bottom of the range around 12 to 14 percent, showing that order volume and profitability don't move together across markets.

Segment-level margin is where the dashboard earns its keep. Channel Partners run a healthy 73.13 percent margin, and within that segment every product from Amarilla to VTT stays in a tight, positive band. Government customers also perform well at 21.69 percent. Midmarket and Small Business segments are positive but thinner, at 27.71 percent and 9.77 percent. Enterprise is the outlier at negative 3.13 percent, and drilling into it shows every single product losing money in that segment, with Carretera the worst performer at negative 6.95 percent. This is the clearest signal in the whole report: Festman Stores is discounting or pricing Enterprise deals in a way that erases profit entirely, even while the segment likely brings in meaningful revenue.

Discount bands reinforce this. High discounts account for 57.76 percent of all discounting activity, more than medium and low bands combined, which lines up directly with the margin compression seen in Enterprise accounts.

Sales by year and month shows a volatile, spiky pattern rather than smooth growth, with sharp peaks late in the year suggesting seasonal or deal-driven spikes rather than steady demand. Paseo, VTT, and Velo are the top three products by sales amount, each in the 18 to 33 million range, and these same products reappear at the top of the Channel Partners margin table, meaning the best-selling products are also the most profitable ones, at least outside of Enterprise.

## Insights Summary

Revenue and order volume grew sharply year over year, but margin quality is uneven across the business. Channel Partners and Government segments are the profit engines. Enterprise accounts are growing in volume but destroying margin, most likely due to heavy discounting, and the High discount band is the biggest driver of that erosion. Germany and France combine strong order volume with the best margins, making them the most efficient markets, while Mexico and the United States generate volume without matching profitability.

## Recommendations

Based on these patterns, Festman Stores would benefit from reviewing discount approval thresholds specifically for Enterprise deals, since that segment is the only one operating at a loss. A closer look at why the High discount band makes up more than half of all discounting would help determine whether this is deliberate strategy or discount creep. Replicating whatever pricing or sales approach works in Germany and France across lower-margin markets like Mexico could also help close the profitability gap without sacrificing volume.

## Tools Used

Power BI Desktop, Power Query, DAX

## Author

Yaminee Rahangdale
GitHub: [yamineerahangdale1-collab](https://github.com/yamineerahangdale1-collab)
LinkedIn: [Yaminee Rahangdale](https://linkedin.com/in/yaminee-rahangdale-96b754397)
