Bookshop Data Analysis – Power BI Dashboard

Overview:This interactive Power BI report analyzes key performance indicators for a fictional library business, focusing on financial trends, user behavior, and book/genre performance.
 Project Goals:

Analyze revenue generated from rentals and purchases

Identify top-performing genres and books

Track reader growth and behavior over time

Explore most-used payment methods

Practice multi-source data modeling in Power BI
 Data Source & Modeling:

Based on a self-created SQL database (Books, Payments, Rentals, Readers, Authors, Dates)

Supplemented with Excel data for "Alternative Payments"

Model follows a star schema with dimDate, factPayments, and other dimensions

Includes custom transformations (e.g., adjusted revenue per year using multipliers in Power Query)

Pages & Insights:

Title Page:

Project name, author info, context.

KPI Dashboard:

Summary of total revenue, return rate, new members, etc.

Donut chart on revenue by payment type

Insight: Most revenue comes from purchases, with credit card as top method.

Trends Over Time:

Monthly revenue, rentals, and member growth from 2018 to 2024

Insight: Revenue peaked in 2023, then declined slightly in 2024.

Reader & Book Analysis:

Top 10 books and top 5 genres by revenue

Insight: Mystery/Thriller and Romance generate highest earnings.

 Tools & Features Used:

Power Query (ETL + data transformation)

Star schema modeling

Measures (DAX), slicers, drill-through

Dynamic visuals and user interactivity

 Challenges & Solutions:

Original data was flat → solved with dynamic year-based scaling logic

Integrated multi-source data (SQL + Excel) for variety

