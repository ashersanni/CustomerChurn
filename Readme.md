## Analysing Customer Churn using Python

Churn rate is an efficient indicator for subscription-based companies. Identifying customers who aren't happy with provided solutions allows businesses to learn about product or pricing plan weak points, operation issues, and customer preferences and expectations to reduce reasons for churn proactively.

### Customer Churn EDA Workflow
1. **Defining problem and goal***: It’s essential to understand what insights you need to get from the analysis. Understand the problem and collect requirements, stakeholder pain points, and expectations.
2. **Establishing data source**: Next, specifying data sources is necessary. Some popular sources of churn data are CRM systems, Analytics services, and customer feedback.
3. **Data preparation, exploration, and preprocessing**: Selected raw historical data for solving the problem requires transformation into a format suitable for analysis. This step can also aid improvement of the overall results due to an increase in the quality of data.

### About the dataset

The sample data tracks a fictional telecommunications company, Telco. It’s customer churn data sourced by the IBM Developer Platform, and it’s available <a href="https://raw.githubusercontent.com/carlosfab/dsnp2/master/datasets/WA_Fn-UseC_-Telco-Customer-Churn.csv" target="_blank">here</a>. It includes a target label indicating whether or not the customer left within the last month, and other dependent features that cover demographics, services that each customer has signed up for, and customer account information. It has data for 7043 clients, with 20 features.

## Exploratory data analysis (EDA)
The EDA has been conducted in Jupyter Notebook making use of python. The project has primarily made use of the Pandas library for data manipulation and analysis and Matplotlib for visualization and graphical plotting. The notebook and analysis can be found <a href="https://github.com/ashersanni/CustomerChurn/blob/main/Churn%20EDA.ipynb" target="_blank" >here</a>.
