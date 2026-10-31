# Sales Data Analysis using Python

## Project Overview

This project focuses on analyzing customer and product sales data using Python. The objective is to explore customer demographics, understand sales distribution across different categories, identify high-performing states and professions, and examine product-level order activity.

The project follows an Exploratory Data Analysis (EDA) approach using data inspection, cleaning, statistical summaries, data aggregation, and visualizations to identify meaningful patterns in the dataset.

## Objectives

- Understand customer distribution by gender and age group.
- Compare sales amounts across customer segments.
- Identify states contributing the highest sales amounts and summed order quantities.
- Analyze product categories based on customer records and sales amount.
- Explore sales distribution across different professions.
- Identify products with the highest summed order quantities.
- Present findings through clear and informative visualizations.

## Dataset Description

The project uses `Sales_Data.csv`, which initially contains **11,257 rows and 13 columns**.

The dataset includes the following information:

- **Customer Details:** User ID, customer name, age, age group, gender, and profession.
- **Geographic Details:** State, zone, and zipcode.
- **Product Details:** Product ID and product category.
- **Sales Information:** Orders and amount.

The supplied dataset does not contain a date column; therefore, this analysis focuses on customer, geographic, product, and sales patterns rather than time-based trends.

## Tools and Technologies

- **Python** — Data analysis
- **Jupyter Notebook** — Analysis environment
- **Pandas** — Data loading, cleaning, manipulation, and aggregation
- **NumPy** — Numerical computing
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical charts and visual exploration

## Project Workflow

### 1. Data Loading and Inspection

- Imported the CSV dataset using Pandas.
- Examined dataset dimensions and column information.
- Checked data types, missing values, and descriptive statistics.
- Used summary statistics to understand the distribution of numerical data.

### 2. Data Cleaning and Preparation

- Removed the completely empty `Zipcode` column.
- Removed rows where all remaining fields were null.
- Standardized the gender value `M` to `Male`.
- Prepared the cleaned dataset for exploratory analysis.

After these cleaning steps, the dataset contains **11,245 rows and 12 columns**.

### 3. Exploratory Data Analysis (EDA)

The notebook explores customer demographics, geographic distribution, product categories, professions, and sales amounts using grouping, aggregation, and visual analysis.

### 4. Data Visualization

Created charts using Matplotlib and Seaborn to make comparisons and patterns easier to understand.

## Analysis Performed

| Analysis Area | What Was Examined |
|---|---|
| Gender Analysis | Customer record counts and total amount by gender |
| Age Group Analysis | Customer distribution and total amount by age group |
| Age & Gender | Comparison of age-group distribution across genders |
| State Analysis | Top states by summed `Orders` and total amount |
| Product Category | Record counts and total amount by category |
| Category & Gender | Comparison of category-wise amount across genders |
| Profession Analysis | Customer record counts and total amount by profession |
| Product Analysis | Top 10 product IDs by summed `Orders` |

## Key Findings

The following findings are based on the supplied dataset after applying the cleaning steps implemented in the notebook.

- **Customer Gender:** The dataset contains 7,837 female records and 3,408 male records.
- **Gender-wise Amount:** Female records account for approximately 74.46 million in total amount, compared with 31.94 million for male records.
- **Leading Age Group:** The 26–35 age group has the highest number of records (4,540) and the highest total amount, approximately 42.59 million.
- **State Performance:** Uttar Pradesh records the highest total amount, approximately 19.38 million, and the highest summed `Orders` value (6,669) among the states.
- **Product Category:** Beauty has the highest total amount among the product categories, at approximately 22.47 million.
- **Profession Analysis:** IT Sector has the highest total amount among the listed professions, at approximately 14.83 million.
- **Product-Level Analysis:** Product ID `P00265242` has the highest summed `Orders` value among the top 10 products, with a value of 187.

These findings describe patterns in the available dataset and should not be interpreted as proof of customer preferences or cause-and-effect relationships.

**Metric clarification:** The `Orders` field is summed as recorded in the dataset. This sum is not necessarily the number of distinct orders. The dataset does not specify a currency symbol for `Amount`, so no currency has been assumed.

## Skills Demonstrated

- Python for Data Analysis
- Data Inspection and Cleaning
- Exploratory Data Analysis (EDA)
- Pandas Data Manipulation
- NumPy Fundamentals
- Grouping and Aggregation
- Descriptive Statistics
- Data Visualization
- Matplotlib and Seaborn
- Analytical Interpretation

## How to Run This Project

1. Clone or download this repository.
2. Ensure `Sales_Data.csv` and `Sales_Data_Analysis.ipynb` are in the same folder.
3. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Open `Sales_Data_Analysis.ipynb` in Jupyter Notebook or JupyterLab.
5. Run the notebook cells in sequence to reproduce the analysis and visualizations.

## Conclusion

This project demonstrates how Python can be used to prepare a dataset, perform exploratory analysis, summarize sales information, and visualize patterns across customer demographics, states, professions, and product categories.

The analysis provides a foundation for understanding the dataset and demonstrates practical use of Python libraries for data analysis and visualization.

## Author

**Prachi Vaishkiyar**

Data Analytics | Excel | Power BI | SQL | Python | Generative AI
