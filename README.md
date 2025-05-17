# powerbi
# Global Malnutrition Trends Analysis (1983-2019)



## Project Overview

This Power BI project provides a comprehensive analysis and visualization of global malnutrition trends observed between 1983 and 2019. The objective is to highlight key patterns, disparities, and insights related to malnutrition indicators (such as stunting, wasting, underweight, and overweight) across different income classifications and geographical regions, with a specific focus on the **Under-5 population**. The project includes an interactive dashboard and a detailed report page to present the findings.

## Dashboard & Report Highlights

The Power BI file (`.pbix`) contains two main pages:

### 1. Dashboard (`Page 1` in the PBIX)

The dashboard provides a high-level, interactive overview of the malnutrition data:
* **Key Metrics:**
    * **Count of Under-5 Population:** `140`
    * **Sum of Survey Sample:** `317M`
    * **Sum of Underweight individuals:** `10.34K`
* **Malnutrition by Income Classification:**
    * **Sum of Stunting (LDC, LID, SIDC):** Visualizes stunting rates by income classification, likely showing higher stunting in lower-income categories, specifically for the Under-5 age group.
    * **Sum of Overweight and Sum of Underweight:** Compares overweight and underweight prevalence across income classifications for the Under-5 population.
* **Sum of Overweight by Country:** A visual breakdown of overweight individuals by country, focusing on the Under-5 age group.
* **Interactive Filters:** Allows users to dynamically filter data on the page or across all pages.

### 2. Report (`Page 2` in the PBIX)

The report page offers a more narrative and detailed summary of the analysis findings:
* **Dataset Summary:**
    * The dataset includes data on `140` **children under five years of age**.
    * Total sum of underweight individuals in the dataset is `10.34K`.
    * Total number of N Survey Samples is `317 million`.
* **Key Insights from Visualizations:**
    * **Line and Stacked Column Chart:** Shows higher income classifications correspond to lower average stunting rates for the Under-5 population, illustrating the significant impact of economic status on child malnutrition.
    * **Ribbon Chart:** Describes that the highest number of overweight individuals (`1088`) is observed in the second income classification category within the Under-5 age group.
    * **Line Chart:** Indicates Kuwait has the highest sum of overweight individuals (Under-5), exceeding `120`.
    * **Gauge Card:** Displays the Sum of Income Classification as `770`.
* **Sum of Income Classification:** A gauge visual showing `770`.

## Project Structure & Methodology

This project followed a systematic approach typical for Power BI development:

1.  **Data Extraction:** Connecting to and importing data from the specified sources.
2.  **Data Transformation & Modeling:** Cleaning, shaping, and establishing relationships between tables within Power Query Editor and the Power BI Desktop data model, ensuring proper handling of Under-5 population data.
3.  **DAX Measures:** Creating calculated columns and measures (using Data Analysis Expressions) to derive key metrics and enable deeper analysis specific to Under-5 malnutrition.
4.  **Visualization Design:** Designing interactive charts, graphs, and summary cards on both the dashboard and report pages.
5.  **Report & Dashboard Creation:** Assembling the final visuals into cohesive and informative pages.
6.  **Insights & Reporting:** Documenting the key findings and narrative as presented in the report page, specifically addressing Under-5 malnutrition.

## Technologies Used

* **Microsoft Power BI Desktop:** The primary tool used for data connection, transformation, modeling, visualization, and report creation.

## Getting Started

To view and interact with this Power BI report, you will need Power BI Desktop installed on your machine.

### Prerequisites

* **Microsoft Power BI Desktop:** Download and install from the official Microsoft website: [https://powerbi.microsoft.com/desktop/](https://powerbi.microsoft.com/desktop/)


### Viewing the Report

1.  **Open Power BI Desktop.**
2.  Go to `File > Open Report > Browse`.
3.  Navigate to the cloned repository folder and select the `malnutrition.pbix` file.
4.  The report will open in Power BI Desktop, allowing you to explore the dashboard and report pages.

## Usage

Once opened in Power BI Desktop, you can:
* **Navigate between Pages:** Use the page tabs at the bottom left (`Page 1` for Dashboard, `Page 2` for Report) to switch between the overview and the detailed insights.
* **Interact with Filters:** Use the slicers and filters on the right pane to drill down into specific data segments related to the Under-5 population.
* **Explore Visuals:** Hover over charts for tooltips, click on data points to cross-filter other visuals on the page.
* **Refresh Data:** If the underlying data sources are accessible and configured for refresh, you can click `Home > Refresh` to update the data.

## Contributing

This project is primarily a visualization and analysis report. However, if you have suggestions for improvements, new analyses, or find any discrepancies, feel free to open an issue or pull request.

1.  Fork the repository.
2.  Make your changes in Power BI Desktop.
3.  Save the `.pbix` file.
4.  Commit your changes and push to your forked repository.
5.  Open a Pull Request describing your changes.


## Acknowledgments

* Microsoft Power BI for providing an excellent platform for data visualization.
