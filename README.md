# Sales Leads - an MLOps approach

*The problem:*

many companies benefit from sales lead systems to capture customers who are likely to close a deal. In this sense, a machine learning lifecycle is ideal for solving the problem, which begins with preparing lead data, goes through prediction, and ends with validation, testing, and monitoring of the model. In our case, what we want to predict is the **target** variable (binary target variable indicating whether the call resulted in a sale ( 1 ) or not ( 0 ).)
Data Description
The dataset consists of three main categories of information:

* Call Data: Includes details specific to each call, such as duration, time of day, and labels indicating sales outcomes (confirmed or not). **The dataset have an imbalance between sales and non-sales calls.**
* Geo Data: Contains location-based features associated with the calls, potentially including zip codes, regions, or geographic coordinates.
* Census Data: Provides demographic and socioeconomic information for the call locations, such as average income, population density, and other relevant attributes.

The workflow was built in Prefect

![Captura de tela 2025-03-24 202340](https://github.com/user-attachments/assets/746f63e3-33a2-44e6-92df-69058fda05cf)

