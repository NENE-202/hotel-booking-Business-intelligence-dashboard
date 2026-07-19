# 🏨 Hotel Booking Business Intelligence Dashboard

An end-to-end Business Intelligence project built with Power BI to analyze hotel booking performance, uncover revenue opportunities, investigate booking cancellations, evaluate seasonal demand, and understand guest behavior.

The dashboard transforms raw hotel booking data into actionable business insights that support strategic decision-making in revenue management, customer experience, and operational planning.
## 📖 Project Overview

The hospitality industry generates large volumes of booking data every day. Without a centralized reporting system, hotel managers may struggle to monitor financial performance, identify booking trends, understand customer behavior, and reduce revenue losses caused by cancellations.

This project develops an interactive Business Intelligence dashboard using Power BI to provide a comprehensive view of hotel performance.

The dashboard enables decision-makers to monitor revenue, booking trends, cancellation patterns, seasonal demand, and guest behavior through four interactive reporting pages:

- Executive Dashboard
- Cancellation Analysis
- Seasonal Analysis
- Guest Experience Analysis

The analysis combines data cleaning, business intelligence, data visualization, and storytelling to support evidence-based decision-making.

## 🎯 Business Problem

Hotel management generates thousands of booking records containing information about reservations, cancellations, guest demographics, room rates, seasonal demand, and customer behavior. However, this operational data is often stored in spreadsheets or transactional systems, making it difficult for decision-makers to gain timely business insights.

Without a centralized reporting solution, management faces several challenges:

- Limited visibility into overall business performance.
- Difficulty identifying the primary drivers of hotel revenue.
- High booking cancellation rates leading to revenue leakage.
- Poor understanding of seasonal demand fluctuations.
- Limited insights into guest behavior and customer value.
- Inefficient decision-making due to fragmented reporting.

As a result, hotel managers cannot quickly identify operational issues, optimize pricing strategies, improve customer experience, or make informed business decisions.

This project addresses these challenges by developing an interactive Power BI Business Intelligence dashboard that transforms raw booking data into meaningful insights for revenue management, operational planning, and strategic decision-making.

## 🎯 Business Goal

The primary goal of this project is to develop an interactive Business Intelligence dashboard that enables hotel management to make data-driven decisions by providing a comprehensive view of business performance.

The dashboard is designed to help management:

- Monitor key business performance indicators (KPIs) in real time.
- Identify the major drivers of hotel revenue.
- Understand customer booking behavior and spending patterns.
- Investigate the factors contributing to booking cancellations.
- Analyze seasonal demand and booking trends.
- Improve pricing and revenue management strategies.
- Enhance guest experience through customer behavior analysis.
- Support strategic planning with interactive and visual reporting.

By transforming raw booking data into actionable insights, the dashboard empowers decision-makers to improve operational efficiency, maximize revenue, reduce cancellations, and deliver better guest experiences.

## 👥 Stakeholders

The dashboard is designed to support decision-making for multiple stakeholders within the hotel business, including:

| Stakeholder | Business Need |
|-------------|---------------|
| General Manager | Monitor overall business performance and profitability. |
| Revenue Manager | Optimize pricing strategies and maximize revenue. |
| Sales & Marketing Team | Identify high-value customer segments and seasonal demand patterns. |
| Reservations Team | Monitor booking trends and cancellation behavior. |
| Operations Manager | Plan staffing levels and resource allocation based on demand. |
| Customer Experience Team | Understand guest behavior and improve service quality. |

# ❓ Business Questions

The analysis is structured around four key business areas to provide a comprehensive view of hotel performance.

## 1. Executive Performance

This section evaluates the hotel's overall business performance.

Business Questions

- What is the hotel's total revenue?
- How many guests were served?
- What is the Average Daily Rate (ADR)?
- What is the overall booking cancellation rate?
- Which hotel type generates the highest revenue?
- Which customer segment contributes the most revenue?

---

## 2. Cancellation Analysis

This section investigates booking cancellation behavior and identifies potential causes of revenue loss.

Business Questions

- Which hotel type has the highest cancellation rate?
- Which market segments experience the most cancellations?
- How does deposit type influence booking cancellations?
- Does booking lead time affect cancellation behavior?
- Which customer groups present the highest cancellation risk?

---

## 3. Seasonal Analysis

This section evaluates seasonal demand patterns and revenue performance throughout the year.

Business Questions

- Which months generate the highest booking volume?
- Which months produce the highest revenue?
- During which months is ADR highest?
- How does length of stay influence revenue?
- What seasonal trends should management prepare for?

---

## 4. Guest Experience Analysis

This section explores customer behavior and guest value.

Business Questions

- Which customer segment generates the highest revenue?
- Does the number of special requests influence ADR?
- Which countries contribute the most revenue?
- What proportion of guests travel as Family versus Non-Family?
- Which customer groups create the greatest business value?

# 🧹 Data Cleaning & Preparation

Before building the dashboard, the dataset was cleaned and validated in **Microsoft Excel** to improve data quality and ensure accurate analysis. The cleaned dataset was then imported into **Power BI**, where additional transformations were completed using **Power Query**.

### Microsoft Excel

The following data preparation tasks were performed:

- Removed duplicate records.
- Checked and handled missing values.
- Corrected inconsistent data formats.
- Standardized date formats.
- Verified numerical fields such as ADR and Revenue.
- Reviewed customer, hotel, and market segment classifications.
- Created additional business columns to support analysis, including:
  - Revenue
  - Total Guests
  - Total Nights
  - Season
  - Cancellation Status
  - Family Type
  - Length of Stay Category

### Power Query

After importing the cleaned dataset into Power BI, additional transformations included:

- Renaming columns for consistency.
- Assigning appropriate data types.
- Creating a **Month Number** column to sort months chronologically (January–December).
- Validating imported data.
- Preparing the dataset for data modeling and visualization.

These preparation steps ensured that the dashboard was built on a clean, consistent, and analysis-ready dataset.

# 🗂️ Data Model

The dashboard was developed using a **single-table analytical model** based on the cleaned **hotel_bookings** dataset.

Since all required business attributes—including hotel type, customer type, market segment, booking status, revenue, ADR, and seasonal information—were available within a single dataset, additional dimension tables were not required.

The model supports interactive filtering and cross-filtering across all report pages while maintaining a simple and efficient structure suitable for exploratory business analysis.

### Data Model Characteristics

- Model Type: Single-table analytical model
- Source Table: `hotel_bookings`
- Storage Mode: Import
- Relationships: Not required (single-table dataset)
- Data Preparation: Microsoft Excel and Power Query
# 📐 DAX Measures

Several DAX measures were created to support business analysis and dashboard interactivity.

### Key Measures

- Total Revenue
- Total Guests
- Total Bookings
- Cancellation Rate
- Average Daily Rate (ADR)
- Booking Count
- Revenue by Hotel Type
- Revenue by Customer Segment
- Average ADR by Month

These measures enabled dynamic calculations, KPI reporting, and interactive filtering across all dashboard pages.
## 📊 Executive Dashboard

### Purpose

Provides management with a high-level overview of hotel performance by monitoring key performance indicators and identifying major revenue drivers.

### Key KPIs

- Total Revenue
- Total Guests
- Average Daily Rate (ADR)
- Cancellation Rate

### Business Value

This page enables executives to quickly assess business performance, identify high-performing customer segments, compare hotel performance, and monitor revenue trends over time.






