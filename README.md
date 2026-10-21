# E-commerce Sales Analysis

## Project Overview

This project explores an **Indian e-commerce orders dataset** to
identify sales patterns, product performance, customer behavior, and
operational trends. The analysis uses Python to clean the data,
calculate key metrics, and create visualizations that can support
data-driven business decisions.

> **Dataset note:** This is a synthetic practice dataset created for
> learning and portfolio development. It does not represent real
> customer transactions.

## Objectives

-   Clean and prepare the dataset for analysis.
-   Analyze revenue by product category, region, and sales channel.
-   Explore monthly sales trends.
-   Understand order-status and payment-method distributions.
-   Identify top products and high-spending customers.
-   Examine repeat-customer behavior and customer ratings.
-   Summarize findings and suggest business recommendations.

## Tools and Libraries

-   **Python**
-   **Pandas** --- data cleaning, grouping, and calculations
-   **Matplotlib** --- chart formatting and visualization
-   **Seaborn** --- statistical and categorical visualizations
-   **Jupyter Notebook** --- interactive analysis

## Dataset

The dataset contains approximately 5,000 generated e-commerce order
records. Depending on the cleaning steps applied, the final row count
may differ.

### Main columns

  Column               Description
  -------------------- --------------------------------------------
  `order_id`           Order identifier
  `order_date`         Date the order was placed
  `customer_id`        Customer identifier
  `customer_age`       Customer age
  `gender`             Customer gender
  `region`             Customer's region
  `city`               Customer's city
  `product_category`   Category of the purchased product
  `product_name`       Product name
  `quantity`           Quantity recorded for the order
  `unit_price_inr`     Unit price in Indian rupees
  `discount_pct`       Discount percentage
  `shipping_fee_inr`   Shipping fee in Indian rupees
  `sales_amount_inr`   Recorded sales amount in Indian rupees
  `payment_method`     Payment method used
  `order_status`       Order status
  `shipping_days`      Shipping duration in days
  `customer_rating`    Customer rating
  `sales_channel`      Channel through which the order was placed

## Project Workflow

### 1. Data cleaning

-   Inspected the dataset and column types.
-   Checked for missing values.
-   Reviewed duplicate records.
-   Handled missing values in selected columns.
-   Checked repeated customer IDs, recognizing that one customer can
    place multiple orders.

**Data-quality note:** Missing-value treatment can affect the analysis.
In particular, filling missing customer ratings with the mean can change
the rating distribution and average. Interpret customer-rating results
with this limitation in mind.

### 2. Exploratory data analysis

The notebook explores the following areas:

-   **Product category analysis:** Total sales by category.
-   **Monthly sales trends:** Changes in sales over time.
-   **Order status analysis:** Counts and proportions of statuses such
    as delivered, cancelled, pending, or shipped, depending on the
    values in the dataset.
-   **Payment method analysis:** Payment-method frequency and sales by
    payment method.
-   **Regional analysis:** Total sales by region.
-   **Product performance:** Top products by revenue and quantity sold.
-   **Customer analysis:** Customer spending and repeat-customer counts.
-   **Sales channel analysis:** Revenue and order counts by channel.
-   **Customer ratings:** Rating distribution, average rating, and
    average rating by category.

### 3. Visualization

Charts are created using Seaborn and Matplotlib to make patterns easier
to understand. The notebook may include bar charts, line charts, and
count plots.

## Key Findings

Fill in this section after reviewing the actual output from your
notebook. Do not report example or assumed values as findings.

-   **Total sales:** ₹\[add result\]
-   **Total unique orders:** \[add result\]
-   **Total unique customers:** \[add result\]
-   **Average order value:** ₹\[add result\]
-   **Highest-revenue product category:** \[add result\]
-   **Highest-sales region:** \[add result\]
-   **Most-used payment method:** \[add result\]
-   **Highest-revenue sales channel:** \[add result\]
-   **Top product by revenue:** \[add result\]
-   **Average customer rating:** \[add result\]
-   **Repeat-customer percentage:** \[add result, if calculated\]

## Business Recommendations

Use the analysis results to support recommendations such as:

-   Promote products and categories that generate strong revenue.
-   Investigate lower-performing regions to identify possible growth
    opportunities.
-   Make commonly used payment methods convenient for customers.
-   Compare sales channels using both revenue and order volume before
    allocating marketing resources.
-   Review low customer ratings to identify potential product or service
    issues.
-   Monitor order statuses and shipping duration to identify operational
    improvement opportunities.

These recommendations should be tailored to the actual results from the
notebook.

## Repository Structure

A suggested repository layout is:

``` text
Ecommerce-Sales-Analysis/
├── ecommerce_orders_india_5000.csv
├── ecommerce_sales_analysis.ipynb
├── README.md
└── images/
    ├── category_sales.png
    ├── monthly_sales.png
    ├── regional_sales.png
    └── payment_methods.png
```

Update the filenames above to match the files you actually upload. The
`images/` folder is optional; add exported charts if you want them to
appear in the README.

## How to Run the Project

1.  Clone or download this repository.

2.  Install Python and Jupyter Notebook, or use a notebook environment
    such as JupyterLab.

3.  Install the required libraries:

    ``` bash
    pip install pandas matplotlib seaborn jupyter
    ```

4.  Open `ecommerce_sales_analysis.ipynb`.

5.  Ensure the CSV path in the notebook matches the location of the
    dataset.

6.  Run the notebook cells in order.

## Limitations

-   The dataset is synthetic and is intended for practice, not
    real-world business reporting.
-   Cleaning decisions, including how missing values are handled, can
    affect results.
-   Confirm the meaning and calculation of `sales_amount_inr` before
    interpreting it as revenue, and avoid double-counting if the dataset
    contains multiple rows per order.
-   Correlation or patterns in this dataset do not establish causation.

## Skills Demonstrated

-   Data cleaning and preparation
-   Exploratory data analysis (EDA)
-   Pandas grouping and aggregation
-   Descriptive statistics and percentage calculations
-   Data visualization with Matplotlib and Seaborn
-   Business interpretation and insight communication
-   GitHub project documentation

## Author

Pagigireddy Bhanuprakash Reddy

# Email
bhanuprakashreddy.p1019@gmail.com

Data Analytics Portfolio Project

------------------------------------------------------------------------

If you use this project in a portfolio, make sure the notebook runs from
beginning to end and replace the placeholders in **Key Findings** with
results from your own analysis.
