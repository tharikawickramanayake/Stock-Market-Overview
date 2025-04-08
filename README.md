# Stock-Market-Overview
This repository showcases interactive Power BI dashboards developed using real-world data sources including APIs like Finnhubdata. Projects focus on business analytics, stock market insights, customer behavior, and logistics.
# Stock Market Overview Dashboard

This Power BI dashboard provides an overview of stock symbol data sourced directly from the [Finnhub API](https://finnhub.io/docs/api#stock-symbol). It enables users to explore and filter listed stocks based on exchange, currency, and type.

---

## Objective

To visualize global stock listings and help users identify trends based on currency, market identifier codes (MIC), and stock types.
(Scheduled refresh supported in Power BI Service (Pro), currently using manual refresh due to license limitations.)

---

## Data Source

- **API**: [Finnhub.io - Stock Symbol Endpoint](https://finnhub.io/docs/api#stock-symbol)
- **Endpoint Used**: `/stock/symbol?exchange=US`
- **Method**: Power Query (Web connector)
- **Fields**: `currency`, `description`, `displaySymbol(user-friendly symbol)`, `figi(unique financial instrument identifiers)`, `mic( Market Identifier Code (like XNAS, BATS, etc.))`, `shareClassFIGI`, `symbol(stock ticker)`, `type(Common Stock, ADR, ETF,etc)`

---

## Tools & Skills

- Power BI Desktop  
- Power Query (API integration)  
- Slicers & Filters  
- Bar Charts, Pie Charts, KPI Cards  
- Custom Dark Theme  
- DAX for basic measures

---

## Key Features

- Total count of available stock symbols
- Pie chart: Distribution by stock type (e.g., Common Stock, ADR)
- Bar chart: Number of symbols per MIC (exchange)
- Currency filter to drill down into regional listings

---

## Insights

- USD is the most common trading currency
- Most securities are “Common Stock”
- NYSE (MIC: XNYS) contains the highest symbol count

---

## Use Case

This dashboard can assist investors, analysts, or financial educators in understanding the structure of market listings and making informed decisions about exchange activity and stock diversity.

---

## Preview

![Stock Market Overview Dashboard](https://github.com/user-attachments/assets/0543c272-b977-471c-9c87-b2b5bed5d3f3)



