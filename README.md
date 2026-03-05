

# App Insight Dashboard – Tableau Project

## Project Overview

This project analyzes Google Play Store app data to identify the key factors behind app success, such as ratings, installs, reviews, category performance, pricing impact, and app size optimization.

The Tableau dashboard is fully interactive and helps stakeholders explore market trends and make data-driven decisions for app development, optimization, and marketing strategy.

---

## Situation

The organization obtained a dataset of **10,000+ Google Play Store apps** containing information such as:

* App ratings
* Number of installs
* User reviews
* App size
* Category
* App type (Free / Paid)
* Update history

Management needed clear answers to business questions like:

* What factors drive app success?
* Which categories dominate installs and engagement?
* Does app size impact installs?
* How do ratings relate to installs and reviews?
* What insights can guide product and monetization strategy?

The raw dataset required cleaning, transformation, and structured visualization to make it suitable for executive-level analysis.

---

## Task

As a **Tableau Developer**, my responsibilities were to:

1. Clean and prepare the dataset for analysis
2. Create meaningful calculated fields and KPIs
3. Design an interactive, multi-page Tableau dashboard
4. Identify actionable insights for decision-makers
5. Present findings in a clear, business-friendly format

---

## Action

### 1. Data Preparation

* Removed duplicate records
* Handled missing and null ratings
* Converted installs and price fields into numeric format
* Standardized app size into MB
* Created calculated fields for:

  * Rating Category (Poor, Average, Good, Excellent)
  * Size Category (Small, Medium, Large)
  * Install Segments (Niche, Emerging, Growing, Viral)
  * High Rating Flag (Rating ≥ 4)

---

### 2. Key Calculations Created

* Total Apps
* Average Rating
* Total Installs (Billions)
* Total Reviews (Millions)
* High Rating %
* Success Score
* Engagement Indicator
* Category-wise Install Share

All calculations respond dynamically to filters and slicers.

---

### 3. Dashboard Pages Designed

#### Page 1 – Executive Overview

* KPI cards (Apps, Rating, Installs, Reviews, High Rating %)
* Top categories by installs
* Free vs Paid app distribution
* Installs by rating category
* App size distribution
* Overall success score indicator

**Purpose:** Provide a high-level summary of the app market.

---

#### Page 2 – Category Insights

* Category-level install and review analysis
* Rating distribution by category
* Install segmentation analysis
* Free vs Paid comparison
* Top-performing apps table

**Purpose:** Identify high-performing and underperforming categories.

---

#### Page 3 – Size vs Installs Analysis

* Scatter plot (App Size vs Installs vs Reviews)
* Category-level comparison
* Insight summary panel

**Purpose:** Evaluate the impact of app size on popularity and engagement.

---

### 4. Advanced Tableau Features

* Interactive filters (Category, Rating Group, Install Segment)
* Drill-down and highlight actions
* Conditional formatting for ratings
* Log-scale analysis for installs and reviews
* Clean and professional dashboard theme
* Business-oriented insight narration

---

## Result

The dashboard delivered several important insights:

### 1. Market Concentration

Game and Communication categories dominate installs and engagement.

### 2. App Size Is Not a Direct Success Factor

Large apps succeed due to value and engagement, not size alone.

### 3. Free Apps Lead the Market

More than 95% of apps are free, highlighting the dominance of freemium and ad-based models.

### 4. High Ratings Drive Growth

Apps with ratings above 4.0 contribute disproportionately to total installs.

### 5. Optimized Medium-Sized Apps Perform Best

Balanced app sizes show better adoption than very large or very small apps.

---

## Business Recommendations

* Prioritize high-demand categories such as Games and Communication
* Optimize app size to improve adoption and retention
* Maintain ratings above 4.0 for competitive advantage
* Focus on freemium monetization strategies
* Track engagement metrics alongside install counts

---

## Tools & Technologies Used

* Tableau Desktop
* Calculated Fields
* Data Cleaning & Preparation
* Interactive Dashboards
* Visual Analytics

---

## Key Skills Demonstrated

* Data Visualization with Tableau
* Business Intelligence Development
* KPI & Metric Design
* Analytical Storytelling
* Executive-level Reporting

---

## Conclusion

This Tableau project demonstrates how large-scale app marketplace data can be transformed into clear, actionable insights. The dashboard acts as a decision-support tool for product teams, marketing managers, and senior leadership.

The analysis confirms that **app success depends more on category demand, engagement, and rating quality than on app size alone**.

![image alt](https://github.com/ParthPatilAnalyst/App-Insight-Dashboard-Tableau-Project/blob/8e406af14b1bdda334a41a893ad836c93393a0c9/Screenshot%202026-03-05%20102504.png)
