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

# 📊 Dashboard Overview

The Power BI report consists of **four interactive dashboard pages**, each designed to answer a specific set of business questions.

| Dashboard Page | Business Focus | Primary Objective |
|----------------|----------------|-------------------|
| Executive Dashboard | Overall Business Performance | Monitor KPIs and revenue performance |
| Cancellation Analysis | Booking Risk | Identify cancellation drivers and revenue leakage |
| Seasonal Analysis | Demand & Revenue Trends | Analyze seasonal booking patterns and pricing opportunities |
| Guest Experience | Customer Behaviour | Understand guest characteristics and spending patterns |

Together, these dashboards provide management with a comprehensive view of hotel performance, enabling faster, data-driven decision-making.



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

# 📈 Executive Summary

This Business Intelligence project analyzes historical hotel booking data to evaluate revenue performance, booking behaviour, cancellation trends, seasonal demand, and guest experience.

The analysis revealed several important findings:

- The hotel generated **$828.26K** in total revenue from **119,390 bookings**, serving approximately **234,988 guests**.
- **Transient-Party** and **Transient** customers contributed the majority of total revenue.
- The overall **cancellation rate of 37%** represents a significant source of revenue leakage.
- **City Hotels** experienced substantially more booking cancellations than Resort Hotels.
- Booking demand and revenue displayed clear seasonal patterns, with peak performance occurring during high-demand months.
- Guests submitting more special requests generally paid higher Average Daily Rates (ADR), indicating higher customer value.

These insights provide hotel management with actionable information to improve pricing strategies, reduce cancellations, enhance customer experience, and support operational planning.

# 🔍 Root Cause Analysis

The dashboard identified several business challenges affecting hotel performance.

## 1. High Booking Cancellation Rate

### Possible Root Causes

- Long booking lead times increase the likelihood of cancellations.
- Flexible deposit policies reduce customer commitment.
- City Hotels receive a larger volume of bookings, resulting in higher cancellation volumes.
- Certain market segments demonstrate consistently higher cancellation behaviour.

### Business Impact

- Revenue loss
- Reduced occupancy
- Inaccurate demand forecasting
- Operational inefficiencies

---

## 2. Revenue Concentration

### Possible Root Causes

- Revenue is heavily dependent on Transient and Transient-Party customers.
- Contract and Group bookings contribute relatively little revenue.

### Business Impact

- Greater business risk if high-value customer segments decline.

---

## 3. Seasonal Demand Fluctuation

### Possible Root Causes

- Travel demand varies significantly throughout the year.
- Room pricing changes based on seasonal demand.

### Business Impact

- Uneven occupancy
- Revenue volatility
- Staffing challenges

---

## 4. Guest Spending Behaviour

### Possible Root Causes

- Guests requesting additional services are willing to pay higher room rates.
- Higher-value guests typically require more personalised services.

### Business Impact

- Opportunities for premium services and upselling.


## 2. Cancellation Analysis

### Purpose

This dashboard investigates booking cancellation behaviour to identify patterns, understand contributing factors, and reduce revenue leakage.

### Key Metrics

- Cancellation Rate
- Cancellation by Hotel Type
- Cancellation by Market Segment
- Cancellation by Deposit Type
- Cancellation by Lead Time

### Key Insights

- City Hotels recorded the highest number of booking cancellations.
- Longer booking lead times were associated with higher cancellation levels.
- Certain market segments consistently experienced higher cancellation rates.
- Non-Refundable deposits significantly reduced cancellation risk.

### Business Value

Supports management in identifying high-risk bookings, improving reservation policies, and reducing revenue losses caused by cancellations.


## 3. Seasonal Analysis

### Purpose

The Seasonal Analysis dashboard evaluates booking demand, pricing trends, and revenue performance across different months of the year.

### Key Metrics

- Booking Count by Month
- Revenue by Month
- Average ADR by Month
- Revenue by Length of Stay

### Key Insights

- Booking demand steadily increased toward the peak travel season.
- August recorded the highest booking volume.
- Monthly revenue peaked during the strongest demand periods.
- Short Stay bookings generated the largest share of total revenue.

### Business Value

Enables management to optimize pricing strategies, improve staffing plans, and prepare for seasonal fluctuations in demand.

## 4. Guest Experience Analysis

### Purpose

This dashboard explores guest behaviour, customer value, and geographic distribution to support customer-focused decision-making.

### Key Metrics

- Revenue by Customer Segment
- ADR vs Special Requests
- Family vs Non-Family Guests
- Revenue by Guest Country

### Key Insights

- Transient-Party guests generated the highest revenue.
- Guests making more special requests generally paid higher ADR.
- Non-Family guests represented the majority of bookings.
- Revenue was generated from a broad international customer base.

### Business Value

Provides insights into customer behaviour that support personalized services, targeted marketing campaigns, and premium guest experience initiatives.

# 💡 Key Business Insights

The analysis produced several important business insights:

### Revenue Performance

- Total hotel revenue exceeded **$828K**, with City Hotels generating the highest overall revenue.
- Transient-Party and Transient customers were the primary contributors to hotel revenue.

### Booking Cancellations

- Approximately **37%** of bookings were cancelled, representing a significant source of revenue leakage.
- Longer lead times and flexible booking conditions contributed to higher cancellation risk.

### Seasonal Demand

- Booking demand increased significantly during peak travel months.
- Revenue and ADR followed clear seasonal patterns, supporting the use of dynamic pricing strategies.

### Guest Behaviour

- Guests submitting multiple special requests generally paid higher ADR.
- Most bookings were made by Non-Family travellers, suggesting that the hotel's primary customer base consists of solo travellers, couples, and business guests.

# 🚀 Business Recommendations

Based on the dashboard insights, the following recommendations are proposed to improve hotel performance.

## 1. Reduce Booking Cancellations

**Business Issue**

Approximately **37%** of bookings were cancelled, resulting in significant revenue loss.

### Recommendations

- Encourage Non-Refundable deposit options through pricing incentives.
- Send automated booking reminders before arrival dates.
- Develop predictive models to identify bookings with a high risk of cancellation.
- Review cancellation policies for high-risk customer segments.

---

## 2. Improve Revenue Performance

### Recommendations

- Prioritize marketing campaigns targeting **Transient** and **Transient-Party** customers.
- Introduce loyalty programmes to encourage repeat bookings.
- Continuously monitor ADR and occupancy to optimise pricing decisions.

---

## 3. Optimise Seasonal Demand

### Recommendations

- Implement dynamic pricing during peak seasons.
- Increase staffing and operational capacity before high-demand periods.
- Launch promotional campaigns during low-demand months to improve occupancy.

---

## 4. Enhance Guest Experience

### Recommendations

- Develop premium service packages for guests requesting additional services.
- Personalise guest experiences using booking behaviour.
- Reward high-value guests through loyalty programmes and exclusive offers.

# 💼 Skills Demonstrated

Throughout this project, the following technical and analytical skills were demonstrated:

### Business Analysis

- Business Problem Definition
- KPI Development
- Business Intelligence Reporting
- Root Cause Analysis
- Data Storytelling
- Business Recommendations
- Decision Support Analytics

### Data Preparation

- Microsoft Excel Data Cleaning
- Data Validation
- Missing Value Handling
- Duplicate Removal
- Data Standardisation

### Power BI

- Power Query
- Data Modeling
- DAX Measures
- Interactive Dashboards
- Slicers and Filters
- KPI Cards
- Drill-down Analysis

### Data Visualisation

- Executive Dashboard Design
- Business Storytelling
- Interactive Reporting
- Performance Monitoring

# 🛠️ Tools Used

| Tool | Purpose |
|-------|----------|
| Microsoft Excel | Data Cleaning and Preparation |
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Transformation |
| DAX | KPI and Measure Calculations |
| GitHub | Project Documentation and Version Control |

# 📁 Project Files

| File | Description |
|------|-------------|
| Hotel_Booking_Power_BI.pbix | Power BI report |
| hotel_bookings.csv | Cleaned dataset |
| README.md | Project documentation |
| Executive_Report.png | Executive Dashboard |
| Cancellation_Report.png | Cancellation Dashboard |
| Seasonal_Analysis_Report.png | Seasonal Dashboard |


# 🔮 Future Improvements

Future enhancements could include:

- Building a Star Schema data model.
- Integrating SQL as the primary data source instead of CSV.
- Developing predictive models for booking cancellations.
- Adding forecasting for future revenue and occupancy.
- Creating row-level security for different business departments.
- Publishing the dashboard to the Power BI Service for online access.


| Guest_Experience_Report.png | Guest Experience Dashboard |


# 📸 Dashboard Preview

The report consists of four interactive dashboards that provide a comprehensive overview of hotel performance.

### Executive Dashboard

*(Insert Screenshot)*

### Cancellation Analysis

*(Insert Screenshot)*

### Seasonal Analysis

*(Insert Screenshot)*

### Guest Experience

*(Insert Screenshot)*


# 👩‍💻 Author

**Esther Ohuenene Emmanuel**

Data Analyst | IBM Certified Data Analyst

Passionate about transforming raw data into actionable business insights through analytics, visualization, and storytelling.

### Connect with Me

- LinkedIn: www.linkedin.com/in/esther-emmanuel-654034292
- GitHub: https://github.com/NENE-202
- Email: emmanueloziowuh@gmail.com
