# 📊 Sales Pulse – Performance & Insights Dashboard

## 1. Project Overview

**Sales Pulse – Performance & Insights** is an interactive sales commission dashboard developed using Microsoft Power BI Desktop. It helps analyze salesperson performance, compare commissions across cities, and understand commission distribution through KPIs, charts, and interactive filters.

The dashboard presents important business insights in a clear and visual format to support data-driven decision-making.

## 2. Project Objectives

- Analyze total and average sales commissions.
- Compare commission performance across different cities.
- Identify top-performing salespeople.
- Understand commission distribution using a doughnut chart.
- Provide interactive filtering for better data exploration.

## 3. Tools and Technologies

- **Visualization Tool:** Microsoft Power BI Desktop
- **Data Analysis:** Power BI
- **Data Modeling:** Relationships and DAX measures, where applicable
- **Visualizations:** KPI Cards, Column Chart, Bar Chart, Doughnut Chart, Slicers

## 4. Dashboard KPIs

The dashboard contains three key performance indicators.

### KPI 1: Average Commission

**Displayed Value: 16.98K**

This KPI displays the average commission value across the sales data.

**Purpose:**
- Understand the average commission performance.
- Evaluate the typical commission amount.
- Compare average commission with overall commission performance.

### KPI 2: Total Commission

**Displayed Value: 509.43K**

This KPI represents the total commission recorded in the dataset.

**Purpose:**
- Measure the overall commission generated.
- Understand total commission performance.
- Provide a high-level summary of commission results.

### KPI 3: Total Salespeople

**Displayed Value: 28**

This KPI displays the total number of salespeople represented in the dashboard.

**Purpose:**
- Understand the size of the sales team.
- Evaluate commission performance across the team.
- Provide context for salesperson-level analysis.

## 5. Charts and Visualizations

### Chart 1: Commission by City

**Visualization Type:** Clustered Column Chart

This chart compares total commission across different cities.

**Cities displayed include:**
- Hyderabad
- Bengaluru
- Singapore
- Cairo
- Goa
- Pune

**Step-by-Step Explanation:**

1. Select a clustered column chart in Power BI.
2. Place the City field on the X-axis.
3. Place the Total Commission measure on the Y-axis.
4. Enable data labels to display commission values.
5. Format the chart title, axes, and colors for readability.

**Business Insights:**
- Compare commission performance across cities.
- Identify cities contributing higher commission values.
- Identify cities with relatively lower commission values.
- Support city-level performance comparisons.

### Chart 2: Top 10 Performers

**Visualization Type:** Horizontal Bar Chart

This chart displays salespeople ranked by their total commission.

**Examples visible in the dashboard:**
- Charles – 95K
- Csk S – 73K
- Bill – 68K
- Jayes... – 63K
- Rachel – 45K
- James – 39K
- Ragu... – 24K

**Step-by-Step Explanation:**

1. Select a clustered bar chart.
2. Add Salesperson Name to the Y-axis.
3. Add Total Commission to the X-axis.
4. Apply a Top N visual-level filter to show the top 10 salespeople by commission.
5. Sort the commission values in descending order.
6. Enable data labels to display the commission values.
7. Add a scrollbar if needed to view the remaining performers.

**Business Insights:**
- Identify high-performing salespeople.
- Compare individual commission contributions.
- Understand performance differences within the sales team.
- Help management recognize strong performers.

### Chart 3: Commission Mix

**Visualization Type:** Doughnut Chart

This chart shows the distribution of salespeople across commission categories, such as Low and High.

The displayed dashboard indicates:
- Low: 21 salespeople (72.41%)
- High: 4 salespeople (13.79%)

The remaining category or value is not fully identifiable from the screenshot.

**Step-by-Step Explanation:**

1. Select a doughnut chart.
2. Add the commission category field to the Legend.
3. Add the appropriate salesperson count or record-count measure to Values.
4. Assign colors to distinguish the categories.
5. Enable data labels to show values and percentages.
6. Add a legend to explain each category.

**Business Insights:**
- Understand how salespeople are distributed across commission categories.
- Compare the size of the Low and High categories.
- Identify the dominant category in the current dashboard view.

*Note: The exact thresholds used to classify commission as Low or High depend on the underlying data and business rules.*

## 6. Interactive Filters

### Filter 1: Salesperson Filter

The salesperson filter allows users to select an individual salesperson or view all salespeople.

**Purpose:**
- Analyze individual salesperson performance.
- Compare commission results under different selections.
- Focus on specific salespeople.

### Filter 2: Cities Filter

The Cities filter allows users to select cities from the available list.

**Purpose:**
- Analyze commission results for selected cities.
- Compare city-level performance.
- Explore how city selection affects the dashboard visuals.

## 7. Dashboard Design

The dashboard is organized into the following sections:

1. **Title Panel:** Displays the project name and dashboard theme.
2. **KPI Section:** Summarizes average commission, total commission, and total salespeople.
3. **City Analysis:** Compares commission values across cities.
4. **Salesperson Analysis:** Highlights the top-performing salespeople.
5. **Commission Mix:** Shows the distribution across commission categories.
6. **Filter Panel:** Provides interactive controls for data exploration.

## 8. Key Findings

Based on the values visible in the dashboard:

- Total commission is displayed as 509.43K.
- Average commission is displayed as 16.98K.
- The dashboard reports 28 salespeople.
- Hyderabad has the highest displayed city commission among the cities shown.
- Charles is the leading salesperson in the visible performer ranking, with 95K commission.
- The Low commission category represents 21 salespeople, or 72.41%, in the displayed chart.

These findings describe the displayed dashboard values and may change when filters are applied.

## 9. How to Use the Dashboard

1. Open the Power BI report.
2. Review the KPI cards to understand overall performance.
3. Explore the Commission by City chart.
4. Review the Top 10 Performers chart.
5. Examine the Commission Mix doughnut chart.
6. Use the salesperson and city filters to explore selected data.
7. Compare the results across the dashboard visuals.

## 10. Project Outcome

This project demonstrates practical skills in Power BI dashboard development, KPI reporting, data visualization, interactive filtering, and business performance analysis.

It provides a consolidated view of sales commission data and makes it easier to explore salesperson and city-level performance.

## 11. Project Files

- `Sales Dashboard.pdf` – Dashboard preview.
- `Sales Dashboard.pbix` – Interactive Power BI report, if included.

## 12. Author

**Prema Sindhu**

Aspiring Data Analyst | Power BI | SQL | Python | Excel | Data Visualization

# Sales-Pulse-PowerBI-Dashboard
Interactive Power BI sales dashboard to analyze commission performance, city-wise commissions, top performers, and commission distribution.
