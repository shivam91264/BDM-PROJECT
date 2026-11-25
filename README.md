# Battery Solutions: A Strategy for Effective Inventory and Sales

**Business Data Management (BDM) Capstone Project | IIT Madras Online BS Degree**

## Project Overview

This project examines the sales and inventory management challenges at **Govind Batteries & Inverter Store**, a battery shop in Katraj, Pune, established in October 2017. The store sells batteries for vehicles, inverters and other uses.

The business was facing recurring shortages of popular battery models. When a required product was unavailable, customers sometimes had to wait or leave without making a purchase. The store also needed a clearer way to review its sales records, understand changes in demand and plan inventory.

For this project, I worked with the store's historical sales data and followed a process covering data collection, data cleaning, exploratory analysis, forecasting and project documentation. The aim was to use the available business data to support more informed decisions about inventory and sales operations.

## Project Objectives

- Understand the store's sales and inventory management challenges.
- Collect and prepare the business's historical sales records for analysis.
- Examine sales and revenue patterns across months and weekdays.
- Analyse sales across battery brands, models and product types.
- Study customer purchase patterns and repeat purchases.
- Review pricing trends and apply demand analysis to selected battery models.
- Explore forecasting methods that can assist with inventory planning.
- Prepare practical, data-based recommendations for the business.

## Business and Dataset

The data was collected directly from Govind Batteries & Inverter Store. The store owner provided the sales records used in the project, along with supporting material documenting the source of the data.

| Item | Details |
|---|---|
| Business | Govind Batteries & Inverter Store |
| Location | Katraj, Pune, Maharashtra, India |
| Business established | October 2017 |
| Data period | February 2024 to October 2024 |
| Data source | Primary sales records provided by the store owner |
| Cleaned dataset | 556 rows and 8 columns |

The dataset includes fields such as bill number, transaction date, customer name and contact number, battery company, battery SKU/model, battery type, quantity and amount in Indian rupees.

Both the original records and the cleaned dataset are included in the project files so that the data preparation process can be reviewed.

## Tools and Technologies

| Tool or library | Use in the project |
|---|---|
| **Microsoft Excel (Advanced)** | Pivot tables, charts, conditional-formatting heatmaps, monthly and product-wise summaries, pricing calculations and the Forecast Sheet tool. |
| **Python** | Data preparation, cleaning and exploratory analysis. |
| **Pandas** | Reading, inspecting, organising and cleaning the sales records. |
| **NumPy** | Numerical operations during data preparation and analysis. |
| **datetime** | Converting and working with transaction dates. |
| **Matplotlib and Seaborn** | Visualisation during data exploration. |
| **Jupyter Notebook / Google Colab** | Writing and running the Python data-cleaning work. |
| **Microsoft Word** | Preparing project reports and documentation. |
| **Microsoft PowerPoint** | Preparing the project presentation. |
| **WordPress** | Supporting the project's web-based presentation work. |

## Project Workflow

### 1. Data Collection

I selected a local business and collected its historical sales records with the owner's support. The project files also include a letter and photographs supplied by the business as supporting material for the data source.

### 2. Data Cleaning and Preparation

I reviewed the structure and quality of the raw data before using it for analysis. The preparation work included:

- Checking column names, data types and missing values.
- Filling missing contact-number entries with `NA` to keep the records consistent.
- Removing extra spaces and standardising the case of battery company and SKU names. This helped ensure that differently formatted versions of the same product were treated consistently.
- Converting the transaction date field into a proper date format for time-based analysis.
- Preparing a separate cleaned dataset for further analysis.

The Python work is documented in `Bdm_data_cleaning_shivam.ipynb`.

### 3. Analysis in Excel and Python

After preparing the data, I used Python for data checks and initial visual exploration. I then used Excel for most of the business analysis. Pivot tables and charts were used to examine sales by month, weekday, customer, brand, battery type and SKU. Conditional formatting was used to create monthly sales heatmaps for selected products.

The analysis work included:

- **Customer analysis:** examining first-time and returning customer activity, along with sales by weekday.
- **Product analysis:** comparing battery brands and models by units sold and revenue.
- **Sales trends:** reviewing changes in sales volume and revenue over the nine-month period.
- **Product-level monthly analysis:** using heatmaps to review how selected battery models performed across months.
- **Pricing analysis:** calculating average selling prices and month-to-month price elasticity.
- **Demand forecasting:** using Excel's Forecast Sheet tool, including confidence bounds, for selected battery models.

### 4. Reporting and Documentation

I documented the project in three reports: the proposal report, mid-term report and final report. Together, these documents cover the business background, problem statement, data source, dataset description, preparation methods, analysis approach and project recommendations.

## Viewing the Project Files

- Open `Bdm_data_cleaning_shivam.ipynb` in Jupyter Notebook, JupyterLab or Google Colab to review the Python data-cleaning work.
- Open `raw_battery_data.xlsx` and `cleaned_battery_data.xlsx` in Microsoft Excel to review the original and prepared datasets.
- Read the reports in order: `proposal_report.pdf`, `mid_term_report.pdf` and `final_report.pdf`.
- Refer to the `Shop letter & photos` folder for supporting material related to the business and data source.

## Scope and Notes

- The project uses sales records covering February to October 2024. The analysis is limited to the period and information available in those records.
- A month with no recorded sales for a particular product does not, by itself, confirm that the product was out of stock. Stock-on-hand records would be required to verify availability.
- Forecasts are estimates based on the historical data available for the selected products. They should be reviewed against actual sales and stock levels before being used for purchasing decisions.
- The recommendations are specific to Govind Batteries & Inverter Store and the scope of this project.

---

**Course:** Business Data Management (BDM)  
**Institution:** Indian Institute of Technology Madras (IIT Madras)  
**Project:** Battery Solutions: A Strategy for Effective Inventory and Sales
