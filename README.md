# Restaurant Sales & Tipping Analytics Dashboard

## Project Overview

The Restaurant Sales & Tipping Analytics Dashboard is an interactive data visualisation project developed using Python and Plotly. It analyses restaurant transactions, customer spending patterns, and tipping behaviour through different visualisation techniques.

The dashboard helps users understand restaurant sales trends and explore relationships between bills, tips, dining periods, and customer characteristics.

## Objectives

- Analyse restaurant sales and customer tipping patterns.
- Understand the relationship between total bills and tips.
- Compare customer tipping behaviour during lunch and dinner.
- Visualise restaurant bill distributions.
- Identify correlations between numerical variables.
- Develop an interactive dashboard for data exploration.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Plotly
- IPyWidgets
- HTML
- CSS

## Dataset

**Dataset:** Plotly Tips Dataset

The dataset contains 244 restaurant transactions with the following attributes:

- Total Bill
- Tip
- Gender
- Smoker Status
- Day
- Dining Time (Lunch/Dinner)
- Party Size

## Data Visualisations

The project implements five different chart types:

1. **Bar Chart:** Displays average tips received on different days of the week.
2. **Scatter Plot:** Shows the relationship between total restaurant bills and tips.
3. **Histogram:** Represents the distribution of restaurant bill amounts.
4. **Box Plot:** Compares tip distributions between lunch and dinner.
5. **Heatmap:** Displays correlations between numerical variables.

## Interactive Features

- Dropdown filters for day, dining period, and gender.
- Dynamic chart updates based on selected filters.
- KPI cards displaying total revenue, average bill, average tip, and transaction count.
- Interactive hover tooltips.
- Zooming and panning.
- Reset filters functionality.

## Project Structure

```text
Restaurant-Analytics-Dashboard/
│
├── Restaurant_Sales_Tipping_Analytics.ipynb
├── Restaurant_Analytics_Dashboard.html
└── README.md
```

## Installation and Execution

### Using Google Colab

1. Open Google Colab.
2. Upload the Jupyter Notebook.
3. Install the required libraries.

```bash
pip install plotly pandas numpy ipywidgets
```

4. Execute the notebook cells sequentially.
5. Explore the interactive dashboard.
6. Generate and download the HTML dashboard.

### Running Locally

Install the required dependencies:

```bash
pip install plotly pandas numpy ipywidgets
```

Open the notebook using Jupyter Notebook or JupyterLab and execute the cells.

## Expected Outcomes

- Understanding of restaurant sales patterns.
- Identification of customer tipping trends.
- Comparison of lunch and dinner transactions.
- Visual analysis of relationships between numerical variables.
- Development of an interactive data visualisation dashboard.

## Conclusion

This project demonstrates how Python-based data visualisation tools can transform raw restaurant transaction data into meaningful insights. By implementing five different chart types and interactive filtering features, the dashboard provides an accessible way to explore restaurant sales and customer tipping behaviour.

## Author

**Name:** Your Name

**Project:** Data Visualisation

**Academic Year:** 2026

**Tools:** Python, Plotly, Pandas and Google Colab
