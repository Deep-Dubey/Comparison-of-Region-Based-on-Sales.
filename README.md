Here’s a **README** file you can use for your GitHub repository to explain the project:

---

# Comparison of Region Based on Sales - Sample Superstore Dataset

This project focuses on analyzing and comparing sales performance across different regions using the **Sample Superstore** dataset. The project is developed in **Tableau** to visualize key sales metrics for selected regions, providing dynamic, interactive insights based on user input.

## Table of Contents
- [Data Segregation](#data-segregation)
- [Creating a Hierarchy](#creating-a-hierarchy)
- [Parameters for Region Comparison](#parameters-for-region-comparison)
- [Calculated Fields for Region Data](#calculated-fields-for-region-data)
- [Key Metrics](#key-metrics)
- [Dashboard Creation](#dashboard-creation)
- [Interactive Map Filter](#interactive-map-filter)
- [Region-Based Colour Coding](#region-based-colour-coding)
- [Map Synchronization and Visual Focus](#map-synchronization-and-visual-focus)
  
## Data Segregation
The dataset is grouped by **Customer Name** and **Order ID** to better organize and analyze customer relationships and their order history. This allows for clearer insights and easier data management, enabling more focused analysis.

## Creating a Hierarchy
A hierarchy for the **Country** variable is created, nested under a folder named **Location**. This allows for intuitive drill-down functionality, from **Country** to **Region** and **State**, enabling a more detailed geographical analysis.

## Parameters for Region Comparison
Two parameters, **Primary Region** and **Secondary Region**, are defined to allow dynamic comparison between two selected regions. All available regions (East, West, Central, South, etc.) from the dataset are included, enabling region-specific filtering and analysis.

## Calculated Fields for Region Data
Calculated fields are created for the **Primary Region** and **Secondary Region**. These fields categorize the data for the two selected regions, which are then used to filter and display information based on user-defined regions on the dashboard.

## Key Metrics
Key sales metrics are created using calculated fields to display relevant information for the selected regions:
- **Total Sales**: The total revenue generated from the region.
- **Average Sales per Order**: The average sales value per order.
- **Number of Customers**: Total unique customers from the region.
- **Number of Orders**: Total number of orders placed.
- **Number of Products in Sale**: The total number of unique products sold.

## Dashboard Creation
A **side-by-side dashboard** is created to display the performance of the two selected regions. Key metrics for **Primary Region** and **Secondary Region** are shown in distinct views to allow for easy comparison of sales trends and regional performance.

## Interactive Map Filter
An interactive filter is applied to the map, allowing users to dynamically select and zoom into specific regions. This filter updates the map based on region selections, providing a clear geographic visual of the sales data.

## Region-Based Colour Coding
Distinct colours are applied to the map based on the selected regions:
- **Primary Region**: Displayed in one colour (e.g., blue).
- **Secondary Region**: Displayed in a contrasting colour (e.g., green).

This makes it easy for users to visually differentiate between the two regions and their associated data.

## Map Synchronization and Visual Focus
Both the **Primary** and **Secondary** region maps are synchronized based on user input. Clicking on a specific region will zoom into the region, updating the map and colour coding accordingly. This provides a clear visual focus on the region's data, helping users concentrate on the region-specific sales metrics.

---

### Repository
Check the full project and code [here](https://github.com/Deep-Dubey/Comparison-of-Region-Based-on-Sales..git).

---

