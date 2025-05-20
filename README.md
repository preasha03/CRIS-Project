# CRIS-Project

Overview
This Power BI report visualizes metro booking and sales data from CRIS, offering insights into token sales, terminal performance, cash flow, and zone-wise distributions. The goal is to support operational decisions by highlighting patterns in sales, booking behaviors, and financial inputs across terminals and time.

⚙️ Tools Used
Power BI Desktop

Oracle SQL Server (Data Source)

DAX (Data Analysis Expressions)

🧠 Problem Statement
To analyze metro booking and sales data over a span of one month, focusing on identifying:

Dates and zones with peak token sales

Terminal-wise cash influx and deposits

Temporal patterns in bookings

Forecasting potential trends

📁 Dataset
The dataset consists of:

Booking timestamps

Token sales

Zone and terminal identifiers

Cash inflow and deposit records

📌 Dashboard Walkthrough
📄 Page 1: Overall Sales Summary
KPI Cards:

Net Booking Sales (238.38K)

Net Token Sales (91.51K)
These provide at-a-glance metrics on financial activity.

Area Charts (with mini trend lines):
Used for both KPIs to give visual cues about volatility and trends.

Table – Shift-Wise Transactions:
Displays location-wise transaction distribution across three operational shifts.

Line Chart with Forecasting:

Title: Booking Trend with Future Analysis

Visual Choice: Area chart with trend line

Why: Emphasizes subtle fluctuations while highlighting increasing trends with a dotted line regression. Supports forecasting by providing temporal momentum insights.

📄 Page 2: Deeper Breakdown
Bar Chart – Dates with Highest Token Sales

Vertical green bars show daily token performance.

Why: Simple and effective for identifying peaks and comparing sales across time.

Pie Charts – Terminal-Wise Cash Influx & Security Deposits

Cash Influx: Shows contribution of each terminal, with clear percentage split.

Security Deposits: Reflects terminal-specific deposit behaviors.

Why: Pie charts work here because the categories are few and the proportion-based insights are key.

Stacked Column Chart – Zone-Wise Sales

Each bar is segmented by ZONE color (ZONE1–ZONE6).

Why: Offers a compact way to compare zone performance over dates while revealing volume distributions.

🎯 Visual Justification & Effectiveness
Visual Type	Justification	Effectiveness
KPI Cards + Trend	Clean snapshot with subtle visual context	Instant metric tracking; trend inclusion adds foresight
Forecasted Line Chart	Adds predictive layer to booking behavior	Guides planning by identifying upward/downward momentum
Stacked Bars	Captures multi-zone sales in one glance	Allows both cumulative and individual zone analysis
Pie Charts	Best for small categorical comparisons (terminals)	Easy to understand contribution split, especially with % labels
Tabular Matrix	Necessary for shift-level detail	Complements visuals with precise numbers

📈 Key Insights
KBEL02 and KBEL99 were the highest-performing terminals in terms of cash influx.

Bookings exhibited a steady upward trend, suggesting growth or seasonality.

Zone 3 consistently contributed the highest to overall token sales.

Security deposits were most frequent through KBEL99, highlighting reliable terminal usage.

🔄 How to Use
Open cris_project.pbix in Power BI Desktop.

Refresh the dataset if connected to the live Oracle SQL Server.

Interact with visuals using slicers and filters for custom insights.

🙌 Credits
Created by Preasha Ghoshal
Internship Project at Centre for Railway Information Systems (CRIS)
Tools: Power BI, Oracle SQL Server, Microsoft Excel
