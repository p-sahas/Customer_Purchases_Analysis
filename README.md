# Analysis of E-Commerce Customer Purchases

This project analyzes a dataset of 2,000 e-commerce customer transactions to understand purchase behavior and inform marketing strategy. The analysis is conducted using R and is presented in an R Markdown (`.Rmd`) file.

## Project Goal

The primary objective is to analyze customer purchase behavior to optimize marketing strategies and website design. This involves exploring customer demographics, behavioral metrics, and transaction data to uncover actionable insights.

## Dataset

The analysis is based on the `customer_purchases.csv` dataset, which includes the following key characteristics:

*   **Customer Demographics**: Region
*   **Behavioral Metrics**: Time spent on site
*   **Transaction Data**: Purchase amounts
*   **Historical Data**: Previous purchases
*   **Promotion Data**: Discount usage

## Analysis Tasks

The project is divided into four main analysis sections:

1.  **Exploratory Data Analysis (EDA)**: Generating summary statistics and visualizations (histograms, boxplots, scatterplots) to understand the data's distribution and identify outliers or missing values.
2.  **Probability Analysis**: Calculating basic and conditional probabilities to understand customer behavior, such as the likelihood of making a large purchase or using a discount.
3.  **Distribution Fitting**: Fitting Poisson and Normal distributions to relevant variables (e.g., number of previous purchases) to model their behavior.
4.  **Predictive Modeling**: Building a linear regression model to predict `purchase_amount` based on `time_spent_on_site` and using it to make predictions.

## How to Run

This project requires R and RStudio.

1.  **Open the `Customer_Purchases_Analysis.Rmd` file** in RStudio.
2.  **Ensure the `customer_purchases.csv` dataset** is in the same directory as the `.Rmd` file.
3.  **Click the "Knit" button** in RStudio. This will execute the R code chunks within the document and generate a PDF report (`Customer_Purchases_Analysis.pdf`) containing the code, outputs, and written interpretations.

## Author

*   GitHub: [p-sahas](https://github.com/p-sahas)

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
