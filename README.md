# culinary_preferences
This is the repository for the culinary preferences project. This project strives to create an end to end data analysis framework, modelling and predicting individual preferences from collected preference data.

It wuill go through all of the steps of data analysis from data acquisition, establishing a data handling system, to creating predictive models for individual taste preferences.

# Project Design
1. Data Acquisition
2. Database Framework
3. Data Cleaning - Database Integration
4. Statistical Analysis
5. Model Testing

# 1. Data Acquisition
The data is acquitred by participants voulentaring their preference scores for the item in question, they can be acquired in different scenarios, but relevant metadata is always recorded so that the impact
of scenario can be approximated. Rating, rater ID and item identity will therefore be the core metrics that are always modelled, while additional metrics are utilized as appropriate.
The gathered data is then aggregated in Excel Spreadsheets to make them analysis.

# 2. Database Framework
The database framework is a relational database designed from scratch in SQL with core rating tables being connected to a dynamic collection of predictors and metadata allwoing for an organic growth of the
aanlysis ecosystem as the project grows.

# 3. Data Cleaning 
The data cleaning and database integration will take the spreadsheet data and transform it to make it available to the database using the Pandas library in Python.

# 4. Statistical Analysis

# 5. Model Testing
