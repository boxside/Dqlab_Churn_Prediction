# Customer Churn Prediction using Machine Learning
 
 ## About
 ### Code and Resources Used 
  **Python Version:** 3.8  
  
  **Packages:** pandas, numpy, matplotlib, seaborn, sklearn, pickles

  **Dataset:**  DQLab
 
 ### list data details : 
 
   * UpdatedAt Periode of Data taken.
   * customerID Customer ID
   * gender Whether the customer is a male or a female (Male, Female)
   * SeniorCitizen Whether the customer is a senior citizen or not (1, 0)
   * Partner Whether the customer has a partner or not (Yes, No)
   * Dependents Whether the customer has dependents or not (Yes, No)
   * tenure Number of months the customer has stayed with the company
   * PhoneService Whether the customer has a phone service or not (Yes, No)
   * MultipleLines Whether the customer has multiple lines or not (Yes, No, No phone service)
   * InternetService Customer’s internet service provider (DSL, Fiber optic, No)
   * OnlineSecurity Whether the customer has online security or not (Yes, No, No internet service)
   * OnlineBackup Whether the customer has online backup or not (Yes, No, No internet service)
   * DeviceProtection Whether the customer has device protection or not (Yes, No, No internet service)
   * TechSupport Whether the customer has tech support or not (Yes, No, No internet service)
   * StreamingTV Whether the customer has streaming TV or not (Yes, No, No internet service)
   * StreamingMovies Whether the customer has streaming movies or not (Yes, No, No internet service)
   * Contract The contract term of the customer (Month-to-month, One year, Two year)
   * PaperlessBilling Whether the customer has paperless billing or not (Yes, No)
   * PaymentMethod The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
   * MonthlyCharges The amount charged to the customer monthly
   * TotalCharges The total amount charged to the customer
   * Churn Whether the customer churned or not (Yes or No)
## Data Handling
* Filtering CustomerID and drop duplicate
* Missing Value Handling (fill with median for every numeric features (ex. Tenure))
* Handling Outlier data
* Standarized features's value
## Churn Prediction
### Numerical variabel EDA
![Figure 1](https://github.com/boxside/Dqlab_Churn_Prediction/blob/main/figure/numeda.png)
### Categorical variabel EDA
![Figure 1](https://github.com/boxside/Dqlab_Churn_Prediction/blob/main/figure/cateda.png)
### Modelling with Logistic Regression
![train log](https://github.com/boxside/Dqlab_Churn_Prediction/blob/main/figure/trainlog.png)
![train log](https://github.com/boxside/Dqlab_Churn_Prediction/blob/main/figure/testlog.png)
### Modelling with Random Forest Classifier
![train log](https://github.com/boxside/Dqlab_Churn_Prediction/blob/main/figure/trainrf.png)
![train log](https://github.com/boxside/Dqlab_Churn_Prediction/blob/main/figure/testrf.png)
### Modelling with Gradient Boost
![train log](https://github.com/boxside/Dqlab_Churn_Prediction/blob/main/figure/traingb.png)
![train log](https://github.com/boxside/Dqlab_Churn_Prediction/blob/main/figure/testgb.png)
