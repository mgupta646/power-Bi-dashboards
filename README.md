# Power BI Dashboards

<p>
  <img src="https://img.shields.io/badge/Power_BI-Desktop-F2C811?style=for-the-badge&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/DAX_·_Power_Query-2A2230?style=for-the-badge" alt="DAX and Power Query">
  <img src="https://img.shields.io/badge/Data_modeling-6A2CA8?style=for-the-badge" alt="Data modeling">
</p>

Five business dashboards, each built to move from a headline KPI to the questions behind it. Every `.pbix` file is in this repo; open it in Power BI Desktop to explore the model, measures and slicers.

| Dashboard | Domain | Highlights |
|---|---|---|
| [AtliQ Hospitality Insights](#atliq-hospitality-insights) | Hotels | Revenue, occupancy, ADR, RevPAR, DSRN, weekly trends |
| [AtliQ Sales Insights](#atliq-sales-insights) | Hardware sales | MySQL source, Power Query cleaning, currency normalization |
| [Superstore Sales & Forecasting](#superstore-sales--forecasting) | Retail | Sales performance and forecasting |
| [HR Analytics](#hr-analytics) | People | Attrition by role, department and demographics |
| [E-commerce Performance](#e-commerce-performance) | Online retail | Sales, profit, quantity, payment-mode and geography mix |

---

## AtliQ Hospitality Insights

<img src="Visuals/hospitality.png" alt="AtliQ Hospitality dashboard" width="100%">

Revenue insights for **AtliQ Grands**, a fictional chain of 5-star hotels in India facing new competition (a [Codebasics](https://codebasics.io) case study).

- **Model:** hotel, room, booking, aggregated-booking and date tables, joined into one star-style model with slicers by city, room class and week
- **Metrics:** revenue, occupancy %, **ADR**, **RevPAR**, **DSRN**, realisation % and cancellation rate, with week-over-week change
- **Insight:** the dashboard supports dynamic-pricing decisions by showing where weekday and weekend demand and platform mix diverge

## AtliQ Sales Insights

<img src="Visuals/SalesInsight.png" alt="AtliQ Sales Insights dashboard" width="100%">

A sales-performance dashboard for **AtliQ Hardware**, whose sales director needed key metrics and trends in one interactive view.

- **Source:** a MySQL database with five tables (customers, products, markets, date, transactions)
- **Preparation in Power Query:** filtered out zero and negative sales and irrelevant markets, normalized USD transactions to INR, and built table relationships
- **Views:** revenue and quantity by year, quarter, region and market; top and bottom products and customers; revenue trend

## Superstore Sales & Forecasting

<img src="Visuals/SuperStore1.png" alt="Superstore sales dashboard" width="100%">
<img src="Visuals/SuperStore2.png" alt="Superstore forecasting dashboard" width="100%">

## HR Analytics

<img src="Visuals/HrAnalytics.png" alt="HR Analytics dashboard" width="100%">

## E-commerce Performance

<img src="Visuals/Ecommerce.png" alt="E-commerce dashboard" width="100%">

Sales, profit, quantity and average order value by state, category, customer and payment mode, with quarterly slicers. [View in Power BI →](https://app.powerbi.com/links/glHq7djgzp?ctid=34bd8bed-2ac1-41ae-9f08-4e0a3f11706c&pbi_source=linkShare)

---

<sub>Built by <b>Mehul Gupta</b> · more dashboards on <a href="https://public.tableau.com/app/profile/mehul.gupta7649/vizzes">Tableau Public</a> · <a href="https://mgupta646.github.io/">Portfolio</a></sub>
