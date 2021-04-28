# Flatiron Phase 3 Project - Telco Co. Customer Churn Predictive Classification Model

## Medium Blog Post - Towards Data Science
For a narrative summary and key insights on this project, please read my blog post [Predict Customer Churn With Precision][3] on Medium.

## Business Problem
Telco Co. wants to deploy customer retention strategies across systems and business processes to reduce customer churn which is currently running as 26.7% of customers. Business requirements include:

- Find the best initial prediction model to classify customer churn risk
- Model performance should do significantly better than using "averages"
- Deliverables should explain the relative influence that each predictor has on the overall model predictions
- Deliverables should suggest potential solutions to reducing customer churn

## Project Deliverable
The project involved analyzing, cleansing, plotting, featurizing and modeling about 7K customers historical data that the churned or were retained. After analyzing and transforming the data, I optimized several classification models using GridSearchCV. Each model was trained on 80% of the historical data and then asked to predict churn scores on the remaining 20% test data. I used the tools and libraries from Python, Numpy, Pandas, Seaborn, StatsModel, and Scikit Learn. Here you can find my [final business presentation][1] and my [Jupyter notebook][2].

## Repository Contents
Below is a list of the contents of this repository - instructions for using them are in the next section.

- README.md: The README for this repo branch explaining it's contents - you're reading it now.
- Telco-Churn-Classification-Model.ipynb: Jupyter Notebook containing background, data sources, scripts, data profiling, cleansing, analysis, feature engineering and models. Extensive comments included.
- Customer_Churn_Classification.pdf: Final business presentation targeting a 5-minute summary pitch
- Tableau Workbooks: Several Tableau workbooks were used for exploratory data analysis and visualization
- data folder: Folder contains source data files available for use in the project
- images folder: A folder for some images of plots used in presentation
- .gitignore: A hidden file that tells git to not track certain files and folders

[1]: <https://github.com/cutterback/p03-telco-churn-model/blob/98e4c3340c17e70fb3b4714a2a721c58affb8c15/Customer_Churn_Classification.pdf> "Customer Churn Predictive Project"
[2]: <https://github.com/cutterback/p03-telco-churn-model/blob/98e4c3340c17e70fb3b4714a2a721c58affb8c15/Telco-Churn-Classification-Model.ipynb> "Jupyter Notebook Telco Customer Churn Prediction Model" 
[3]: <https://towardsdatascience.com/predict-customer-churn-with-precision-56932ae0e5e3?sk=3c42d8b0df41d75270a14d7aab819dd7> "Towards Data Science Article - Predict Customer Churn With Precision" 

