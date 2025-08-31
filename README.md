# Classic Model Data Visualization using Power BI

## Overview
This repository contains a **Power BI Dashboard** built on the **Classic Models dataset**.  
The dashboard provides interactive visualizations and insights into company performance across sales, products, customers, payments, and employees.

The goal of this project is to demonstrate business reporting capabilities in Power BI using a relational dataset.

---

## Repository Contents
- **Dashboard**
  - `ClassicModelDashboard.pbix` – Main Power BI Desktop file with data modeling and visuals.
- **Datasets (CSV files)**
  - `customers.csv` – Customer information including contact details and country.
  - `employees.csv` – Employee details and office associations.
  - `offices.csv` – Office locations and regions.
  - `orders.csv` – Order header details.
  - `order details.csv` – Order line items with quantities and prices.
  - `payments.csv` – Customer payments with invoice details.
  - `productlines.csv` – Product categories and descriptions.
  - `products.csv` – Product details linked to product lines.

---

## Getting Started

### Prerequisites
- Install **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)** (latest version recommended).
- Ensure all `.csv` files remain in the same directory structure to maintain data connections.

### Steps to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Sushant332/Classic-Model-Data-visualization-using-PowerBI.git
2. Open Power BI Desktop.

3. Load the file ClassicModelDashboard.pbix.

4. If prompted, verify dataset paths or refresh data.

---

## Dashboard Features

The Power BI dashboard provides the following insights:

- Sales Overview
Analysis of total sales trends over time, segmented by region and product.

- Top Products & Product Lines
Ranking of top-selling products and categories.

- Customer Analysis
Breakdown of customer orders, payments, and geographic distribution.

- Employee & Office Performance
Metrics showing sales contributions by employees and office locations.

- Payment Insights
Tracking payment patterns across customers and time.

---

## Data Model

The dataset follows a relational schema with the following key relationships:

- customers ↔ orders ↔ order details

- products ↔ order details

- productlines ↔ products

- employees ↔ customers (via sales representatives)

- offices ↔ employees

- customers ↔ payments

This structure enables cross-analysis across sales, products, and geography.

---

## Usage & Customization

- Refresh data if CSV files are updated.

- Extend dashboard by adding new visuals or measures.

- Apply filters to analyze specific products, customers, or time periods.

---

## License

This project is open-source. You may use and modify it for educational or professional purposes.

---

##   Contributing

Contributions are welcome. To contribute:

1. Fork the repository.

2. Create a feature branch.

3. Commit changes with clear messages.

4. Submit a pull request.


---

## Screenshot

![Sales Overview](images/ps1.png)

![Product Performance](images/ps2.png)

![Customer Analysis](images/ps3.png)

![Employee Performance](images/ps4.png)
