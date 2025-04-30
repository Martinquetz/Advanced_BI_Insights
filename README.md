# Advanced_BI_Insights
This comprehensive, interactive Power BI dashboard harnesses advanced DAX calculations, custom visualizations, and dynamic filtering to deliver deep business intelligence insights. This project exemplifies innovative design through features like smart tooltips, bookmarks, and a centralized filter page.


## Table of Contents

- [Overview](#overview)
- [Dataset & Sources](#dataset--sources)
- [Features & Advanced Design Elements](#features--advanced-design-elements)
- [Dashboard Pages](#dashboard-pages)
  - [Page 1: Business Sales and Profit Overview](#page-1-business-sales-and-profit-overview)
  - [Page 2: Management Revenue & Profit View](#page-2-management-revenue--profit-view)
  - [Page 3: Managers Revenue & Profit View](#page-3-managers-revenue--profit-view)
  - [Page 4: Metrics Review](#page-4-metrics-review)
  - [Filter Page](#filter-page)
  - [Active Filters & Applied Filters Panel](#active-filters--applied-filters-panel)
  - [Custom Tooltip Displaying High-Level Business Overview](#custom-tooltip-displaying-high-level-business-overview)
- [Technologies & Tools](#technologies--tools)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributors & License](#contributors--license)
- [Acknowledgments](#acknowledgments)

---

## Overview

This project is a dynamic, interactive Power BI dashboard designed to present financial and operational insights through custom-designed pages. Leveraging advanced DAX calculations and DAX Studio for debugging and optimization, the dashboard offers a seamless user experience with:

- **Custom Tooltips:** Delivering rich, contextual insights on hover.
- **Smart Bookmarks:** Facilitating effortless navigation and storytelling.
- **Centralized Filter Page:** Controlling analytics across all pages with dynamic filtering.
- **Active Filters Panel:** Visually displays which filters are active to enhance transparency.
- **Crisp Organization:** Meticulous layout and page segmentation for intuitive data exploration.

---

## Dataset & Sources

  - **The Origin of the Data:** Where the dataset comes from, Kaggle.com - an open-source data repository.

  - **Link to the Dataset:** Direct URL https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting .

  - **Additional Context:** The dataset was a record of retail sales of a global superstore for 4 years. I conducted relevant cleaning, EDA, and transformation processes to enable analysis.


---


## Features & Advanced Design Elements

- **Custom Visualizations:** Intuitive charts and KPIs that capture key performance metrics.
- **Advanced DAX Calculations:** Robust formulas drive real-time insights and trend analysis.
- **DAX Studio Integration:** Ensures optimized query performance and easier troubleshooting.
- **Interactive Filtering:** A dedicated filter page that controls all report pages and features an active filters panel.
- **Responsive User Experience:** Bookmark navigation and custom tooltips ensure interactive, in-depth data exploration.
- **Crisp Report Organization:** Thoughtful page design that segments analysis into clear, focused views.

---

## Dashboard Pages

### Page 1: Business Sales and Profit Overview
- **Purpose:** Provides a high-level view of overall sales and profitability.
- **Highlights:** Key financial KPIs, revenue breakdowns, and profit trends visualized with advanced charts and custom tooltips.
- 
![superstore-overview](https://github.com/user-attachments/assets/8f807e28-f5e7-4116-a464-a2e9154ba521)


### Page 2: Management Revenue & Profit View
- **Purpose:** Delivers deep financial insights for management-level decisions.
- **Highlights:** Regional revenue analysis, sales growth trajectories, and product performance comparisons supported by interactive elements.

![management-view](https://github.com/user-attachments/assets/0bcdaf83-c996-4664-ae2b-09177c1c27d3)


### Page 3: Managers' Revenue & Profit View
- **Purpose:** Enhances decision-making with detailed revenue and profit analytics.
- **Highlights:** Scatter plot analyses, cost breakdowns, and year-on-year profitability metrics for nuanced performance insights.

![manager-view](https://github.com/user-attachments/assets/cf34f47d-2c9b-4b99-b225-b93368531410)


### Page 4: Metrics Review
- **Purpose:** Offers a comprehensive sales performance review across multiple dimensions.
- **Highlights:** Category-wise revenue insights, delayed order tracking, and continent-based growth analytics presented through detailed visualizations.

![metric-view](https://github.com/user-attachments/assets/bdbbab00-f2c5-4fe7-9533-bdd986a06a3c)


### Filter Page
- **Purpose:** Acts as the centralized control hub for filtering data across all pages.
- **Highlights:** Dynamic filter options (year, month, product category, customer type, etc.) that immediately update insights across the dashboard.

![filter-page](https://github.com/user-attachments/assets/39d960aa-fbd6-4978-a9da-9ad949b0f343)


### Active Filters & Applied Filters Panel
- **Purpose:** Displays which filters are currently active to ensure clarity in the data context.
- **Highlights:** An interactive panel that shows selections like “Year = 2014” and “Order Priority = High,” along with filter reset and navigation features.

![buttons-n-active-filters](https://github.com/user-attachments/assets/5370f37f-76db-408a-b5e8-0a658c27ff6c)


### Custom Tooltip Displaying High-Level Business Overview
- **Purpose:** Summarizes overall financial performance, focusing on profitability and sales trends.
- **Highlights:** Total profit, shipping costs, profit margins, and geographic mapping of orders complete with custom tooltips and trend lines.

![tooltip](https://github.com/user-attachments/assets/08b03574-57fd-4a32-87be-d9e7661caefd)


---

## Technologies & Tools

- **Power BI Desktop:** For dashboard creation and report design.
- **DAX & DAX Studio:** To develop and optimize advanced calculations.
- **Custom Visuals & Bookmarks:** For interactive storytelling and navigation.
- **Excel:** For data importation, transformation, and integration.

---

## Installation & Setup

### Prerequisites
- **Power BI Desktop:** Ensure you have the latest version installed.
- **Data Files:** All necessary datasets should be included in the repository or referenced correctly.

### Instructions
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/advanced-sales-profit-dashboard.git
   cd advanced-sales-profit-dashboard
   ```
Open the Dashboard

Launch Power BI Desktop and open the .pbix file.

Explore the Dashboard

Use the bookmarks, custom tooltips, and filter page to navigate and interact with the data.

Usage
Interactivity: Utilize the centralized filter page to adjust data views across all pages.

Navigation: Use the built-in bookmarks to switch between detailed analytical pages quickly.

Tooltips & Insights: Hover over data points to see custom tooltips with in-depth information.

Performance Tuning: For advanced users, leverage DAX Studio to review and optimize DAX queries.

## Project Structure

advanced-bi-insights-dashboard/

├── dashboard.pbix       # Will be supplied on request

├── README.md            # This documentation file

└── data/                # Excel dataset for raw transformation of data



## Contributors & License

**Created by:** Martin Unukpo

**Contributions:** Contributions and suggestions to improve the dashboard are welcome!

## Acknowledgments

A heartfelt thanks to the Power BI community and all the open-source resources that inspired the design of this dashboard. Your innovative ideas helped shape the advanced features showcased here.

