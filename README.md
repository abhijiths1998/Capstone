# Capstone
* **Problem Objective**
    * The main aim is to help the client Sigma Cabs to become a full fledged cab aggregator by building a production level model based on the 'Surge_pricing_type' target variable which was calculated by the clients themselves based on the experience in the taxi industry for last 10 months.
* **Procedure**
    * Reading the data
    * Cleaning tha data (Null values imputation)
    * Statistical testing
    * Initial performance check (Without SMOTE)
    * SMOTE-NC (Categorical Variant) for rectifying Class Imbalance
    * Modelling (We used 7 models and considered f1-weighted as the measure)
    * Deployment (using flask , pickle and HTML5 with internal CSS) 
* **Techniques Used**
    * Pandas
    * Numpy
    * SimpleImputer (Null Values)
    * Seaborn
    * Matplotlib.pyplot
    * Sklearn libraries   
* **Outcome**
    * We were able to acheieve a f1-weighted score of 0.81 with a bias error around 19%. We used stacking model as the final model 
