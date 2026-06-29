# Bank Marketing Campaign Analysis — Power BI Dashboard

## Project Description

This project was completed as part of the **DataBoom Summer Data Analytics Marathon**.

The main goal of the project was to analyze a bank marketing dataset and create an interactive **Power BI dashboard** to evaluate the effectiveness of direct marketing campaigns.

The dataset contains information about marketing campaigns of a Portuguese bank. These campaigns were conducted through phone calls, and in many cases, several calls were required before a client decided whether to subscribe to a term deposit.

## Dataset

The dataset was taken from Kaggle:

**Bank Marketing Dataset**
https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset

The dataset contains:

* 11,162 records
* 17 features
* 7 numerical features
* 10 categorical features

The target variable shows whether the client subscribed to a term deposit.

## Tools and Technologies

* Python
* pandas
* Power BI
* DAX
* Kaggle Dataset
* Power BI Custom Visuals

## Exploratory Data Analysis

Before creating the Power BI dashboard, Exploratory Data Analysis was performed in Python.

The EDA included:

* Dataset overview
* Checking missing values
* Searching for duplicate records
* Analyzing unique values in each column
* Reviewing numerical and categorical features
* Preparing the data for visualization in Power BI

## Power BI Dashboard

An interactive Power BI dashboard was created to analyze customer behavior and marketing campaign performance.

The dashboard includes the following visual elements:

* 2 Slicers
* Card
* 2 Advanced Cards
* Stacked Column Chart
* Clustered Column Chart
* Scatter Chart
* Dot Plot by MAQ Software

Additional visuals were installed through **Get More Visuals**:

* Advanced Cards
* Dot Plot by MAQ Software

## Key Metrics

Custom measures were created using **DAX** to evaluate the effectiveness of the marketing campaign.

### Conversion %

This metric shows the percentage of clients who subscribed to a term deposit.

### Successful Subscriptions

This metric shows the number of clients who successfully subscribed to a term deposit.

These metrics are important for understanding how effective the bank's marketing campaign was.

## Age Group Analysis

For customer segmentation, an **Age Groups** feature was created in Power BI using the **New Group** function based on the `Age` column.

This helped analyze how client behavior differs across different age categories.

## Dashboard Insights

The dashboard helps answer the following questions:

* How many clients subscribed to a term deposit?
* What is the overall conversion rate?
* Which age groups are more likely to subscribe?
* How do customer characteristics affect subscription behavior?
* What patterns can be identified from the marketing campaign data?

## Skills Demonstrated

* Data cleaning
* Exploratory Data Analysis
* Power BI dashboard development
* DAX measure creation
* Data visualization
* Customer segmentation
* Marketing campaign analysis
* Business metrics analysis

## Dashboard Preview

[Dashboard Preview](screenshot/dashboard.png)

## Conclusion

This project demonstrates how Python and Power BI can be used together to analyze marketing campaign data, create key business metrics, and present insights through an interactive dashboard.

The final dashboard provides a clear overview of customer behavior and marketing campaign performance.
