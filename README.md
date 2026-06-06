# Customer_behaviour_analysis
My first Data analytics project. In this project i learned about the various tools and practiced what happens in an actual project. Here i did analysis of customer bevaiour by using python, mysql and power BI.

# Data Analytics Project
Overview
This project demonstrates an end-to-end data analytics workflow, starting from raw data extraction to business insights visualization. The project involves data loading, exploratory data analysis (EDA), data cleaning, SQL-based analysis, dashboard development in Power BI, and presentation of findings through reports and slides.
The objective is to transform raw data into meaningful insights that support data-driven decision-making.

## Dataset
The dataset used in this project contains structured data related to business operations, customer behavior, sales performance, or other analytical domains.
### Dataset Features
* Multiple attributes and records
* Numerical and categorical variables
* Missing values and inconsistencies requiring preprocessing
* Suitable for statistical analysis and visualization
* 
## Tools & Technologies

| Tool                              | Purpose                             |
| --------------------------------- | ----------------------------------- |
| Python                            | Data loading, cleaning, and EDA     |
| Pandas                            | Data manipulation and preprocessing |
| SQL (MySQL)                       | Data querying and analysis          |
| Power BI                          | Interactive dashboard creation      |
| Jupyter Notebook                  | Analysis and documentation          |

## Project Workflow

### 1. Data Loading

* Imported dataset into Python.
* Verified data structure and column information.
* Performed initial inspection of records.

### 2. Exploratory Data Analysis (EDA)

* Examined data distributions.
* Identified trends, patterns, and outliers.
* Generated visualizations for key metrics.
* Analyzed relationships between variables.

### 3. Data Cleaning

* Handled missing values.
* Removed duplicate records.
* Corrected inconsistent data formats.
* Standardized column names and data types.

### 4. SQL Analysis

* Imported cleaned data into a relational database.
* Executed SQL queries for:

  * Data aggregation
  * Filtering and sorting
  * Joins and subqueries
  * Business performance analysis

Supported databases:
* MySQL
  
### 5. Power BI Dashboard

Developed an interactive dashboard to visualize:

* Key Performance Indicators (KPIs)
* Trends and patterns
* Category-wise performance
* Comparative analysis
* Business insights

### 6. Reporting

Prepared a detailed analytical report including:

* Project objectives
* Methodology
* Findings
* Recommendations
* Conclusion

### 7. Presentation

Created a professional presentation using Gamma to communicate:

* Project summary
* Analysis process
* Dashboard highlights
* Key insights and recommendations

## Dashboard Highlights
Key dashboard features include:
* Interactive filters and slicers
* KPI cards
* Trend analysis charts
* Category comparisons
* Drill-down capabilities
* Business performance metrics

## Results & Insights

The analysis provided insights into:

* Overall performance trends
* High-performing categories and segments
* Areas requiring improvement
* Data-driven recommendations
* Business opportunities and risks

The dashboard enables stakeholders to monitor performance and make informed decisions efficiently.

## Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── eda_analysis.ipynb
│
├── sql/
│   └── queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── reports/
│   └── project_report.pdf
│
├── presentation/
│   └── gamma_presentation.pptx
│
└── README.md
```

---

## How to Run

### Prerequisites

* Python 3.x
* Jupyter Notebook
* PostgreSQL/MySQL/SQL Server
* Power BI Desktop

### Steps

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Install required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy
```

3. Open the Jupyter Notebook and run the analysis:

```bash
jupyter notebook
```

4. Import the cleaned dataset into your SQL database.

5. Execute SQL queries from the `sql` folder.

6. Open the Power BI dashboard file (`.pbix`) to explore visualizations.

7. Review the report and presentation for project findings.

---

## Conclusion

This project showcases the complete data analytics lifecycle, including data preprocessing, exploratory analysis, SQL-based querying, dashboard development, and business reporting. It demonstrates practical skills in Python, SQL, Power BI, and data storytelling that are widely used in industry analytics projects.

