# Information Visualization: Assignment 3 (Vega-Lite)

**Live Demo:** [https://nishant3122.github.io/Info-Viz-Assignment3/](https://nishant3122.github.io/Info-Viz-Assignment3/)

## Overview
This project is a declarative, interactive data visualization dashboard built using [Vega-Lite](https://vega.github.io/vega-lite/). It analyzes a dataset of sales orders (`SalesOrders.csv`) to uncover trends in sales representative performance, item distribution, and revenue over time. 

The dashboard leverages Vega-Lite's `vconcat` operator to combine five distinct views into a single cohesive layout.

## Included Visualizations
1. **Total Sales by Rep (Donut Chart):** Shows the overall contribution of each sales representative to the total sales volume.
2. **Total over Time by Item (Streamgraph):** A centered area chart displaying the flowing distribution of total sales for different items across months/years.
3. **Trellis Histogram of Units by Item:** A faceted view of unit distributions, complete with an overlaid rule mark indicating the mean for each specific item.
4. **Units vs. Total (Interactive Scatterplot):** Explores the correlation between units sold and total revenue. Features an **interval brush selection** that grays out unselected points for focused analysis.
5. **Average Units by Rep (Interactive Bar Chart):** Compares average unit sales across representatives, featuring a **mouseover hover** interaction to highlight individual bars.

## Technical Architecture
* **Framework:** Vega-Lite (v5)
* **Data Source:** Static CSV (`SalesOrders.csv`) 
* **Deployment:** Static HTML page hosted via GitHub Pages.

## How to Run Locally
Because this project uses static files and native web technologies, no build steps or heavy dependencies are required.
1. Clone this repository to your local machine.
2. Ensure both `index.html` and `SalesOrders.csv` are in the same directory.
3. Open `index.html` in any modern web browser.
