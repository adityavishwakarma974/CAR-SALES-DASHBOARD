🚗 DriveMetrics: Global Car Sales Dashboard

An interactive Power BI report built to track and analyze car sales performance across models, countries, and sales channels — from a 5-year executive overview down to a single model's year-by-year economics.

📌 Short Description / Purpose

The **Car Sales Dashboard** is a visually engaging, drill-through-enabled Power BI report designed to help users explore and compare car sales performance across **multiple models, countries, and sales channels** from 2019–2023. The dashboard highlights revenue trends, unit sales, channel mix, and pricing, letting anyone move from company-wide KPIs to a single model's detailed history in just a few clicks. This tool is intended for use by sales managers, dealership analysts, and business stakeholders who need a fast, self-service way to understand what's driving revenue.

🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

📊 Power BI Desktop** — Main data visualization platform used for report creation
📂 Power Query** — Data transformation and cleaning layer for reshaping and preparing raw sales data
🧠 DAX (Data Analysis Expressions)** — Used for time-intelligence measures (Revenue PY, YoY % growth), dynamic KPI cards, and conditional formatting
🔖 Bookmarks & Buttons** — Custom filter flyout panel and page navigation
📝 Data Modeling** — Relationships established between sales, model, and date tables to enable cross-filtering and drill-through
📁 File Format** — `.pbix` for development and `.png` for dashboard previews
📈 Excel** — Initial dataset structuring before load into Power BI

🗂️ Data Source

*Source: Car sales transaction dataset (2019–2023).*

Data covering car sales across multiple countries and regions, including model-level details (quantity sold, revenue, average price), sales channel (Wholesale, Dealership, Online), and time dimensions (year, month, weekday) — enabling both high-level trend analysis and granular, per-model performance tracking.

✨ Features / Highlights

🎯 Business Problem

Dealership and automotive sales data often lives scattered across spreadsheets — revenue tracked separately from unit sales, channel performance reviewed manually, no single view connecting country-level and model-level performance.

Key questions such as:
- Which models are actually driving revenue?
- Which sales channel converts best — Wholesale, Dealership, or Online?
- How does this year's performance compare to last year?
- Which countries are outperforming or underperforming?

...are difficult to answer quickly from raw, disconnected data.

🚀 Goal of the Dashboard

To deliver an interactive visual tool that:
- Enables users to explore car sales performance globally, by model and by channel
- Supports decisions such as inventory planning, channel investment, and regional sales strategy
- Uncovers year-over-year trends in revenue, volume, and pricing at both a company-wide and individual-model level

🔍 Walkthrough of Key Visuals

- **Revenue & Revenue PY by Year (Combo Chart)**
  Tracks total revenue against the prior year across 2019–2023, with a period summary card showing **$51.58M** in total revenue and **+26.4%** year-over-year growth.

- **Time Granularity Tabs (Year / Month / Weekday)**
  Lets users toggle the entire dashboard view between yearly, monthly, and weekday-level detail without leaving the page.

- **Top Selling Models (Scrollable Gallery)**
  Ranks models by units sold, with each card clickable to drill through into a dedicated model detail page.

- **Most Expensive Models (Highlight Card)**
  Surfaces the highest average-price model at a glance — currently the top model at **$77.4K** average price.

- **Qty Sold by Country (Sortable Table with Sparklines)**
  Country-level breakdown of units sold and revenue, with embedded sparkline trend lines and sortable columns for fast ranking.

- **Qty Sold by Channel (Donut Chart)**
  Breaks down unit sales across **Wholesale (43%)**, **Dealership (32%)**, and **Online (25%)** to show which channel drives the most volume.

- **Qty Sold by Year (Clustered Bar Chart)**
  Compares current year vs. prior year unit sales side-by-side for quick YoY volume comparison.

- **Model Detail Pages (Drill-Through)**
  Clicking any model opens a dedicated page with its product image, average price, and a full year-by-year table of quantity sold and revenue — for example, the top-selling model recorded **666 units** and **~$52M** in lifetime revenue across five years.

- **Custom Filter Panel**
  A "Show Filter" flyout with slicers for **Year, Region, Channel, Model, and Country**, plus a "Clear all slicers" reset — letting users reframe the entire report without hunting through separate visuals.

💼 Business Impact & Insights

- **Channel Strategy**: Sales leaders can see Wholesale is the dominant channel (43%) and use this to guide channel investment and partner negotiations.
- **Model Portfolio Decisions**: Identifying top-selling vs. most-expensive models separately helps balance volume strategy against premium positioning.
- **Regional Performance Tracking**: Country-level sparklines make it easy to spot which markets are accelerating or slowing without digging into raw numbers.
- **Trend-Based Planning**: The 26.4% YoY revenue growth, visible directly on the executive view, gives leadership a fast health check before diving into details.
- **Self-Service Analysis**: The filter panel and drill-through navigation mean stakeholders can answer their own questions without needing a new report built for every ask.

🖼️ Screenshots / Demos

(dashboard screenshots here — Executive Dashboard view, Model Detail page, and Filter Panel)

Executive Dashboard view:- https://github.com/adityavishwakarma974/CAR-SALES-DASHBOARD/blob/main/Dashboard.png

Model Detail:- https://github.com/adityavishwakarma974/CAR-SALES-DASHBOARD/blob/main/Model.png

Filter Panel:- https://github.com/adityavishwakarma974/CAR-SALES-DASHBOARD/blob/main/Show%20Filter.png

🤝 Let's Connect

I'm actively building my data analytics portfolio and preparing for Data Analyst roles. Feedback from fellow analysts is always welcome — and if you're hiring, I'd love to connect!

**Skills demonstrated:** Power BI • DAX • Power Query • Data Modeling • Data Visualization • Dashboard UX Design
