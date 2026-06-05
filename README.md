**Loan Data Analysis & Prediction**

**Overview**

This project focuses on analyzing loan data and predicting loan amounts using machine learning. It includes data preprocessing, visualization, risk classification, and regression modeling.




**Features**


● Data cleaning and preprocessing



●  Exploratory Data Analysis (EDA)


● Loan default analysis


● Risk level classification


● Data visualization using Matplotlib, Seaborn, and Plotly


● Machine Learning model (Linear Regression)


 ●Model performance evaluation



 
**Technologies Used**


● Python 


● Pandas


● NumPy


● Matplotlib


● Seaborn


● Plotly


● Scikit-learn




**Dataset Information**

The dataset includes key loan-related features:

● loan_amnt – Loan amount


● term – Loan duration


● int_rate – Interest rate


● annual_inc – Annual income


● emp_length – Employment length


● home_ownership – Home ownership status


● purpose – Loan purpose


● loan_status – Loan status (Default / Non-default)




**Data Processing Steps**


● Removed missing values


● Converted loan term into numeric format


● Selected important features


● Cleaned and structured dataset




**Analysis Performed**


**Statistical Insights**

● Average Loan Amount


● Average Income


● Interest Rate Distribution



**Visualizations**


●  Loan Status Distribution


●  Loan Amount vs Interest Rate


●  Income vs Loan Amount


●  Histograms (Loan & Income)


●  Boxplots (Outlier Detection)


●  Correlation Heatmap




**Risk Classification**


Loan risk is categorized based on interest rate:


● Low Risk (< 10%)


●  Medium Risk (10% - 20%)


●  High Risk (> 20%)



**Machine Learning Model**


● Model Used: Linear Regression


● Input Features:
Annual Income
Interest Rate
Loan Term


● Target Variable:
Loan Amount




**Model Evaluation**


● R² Score


● Mean Absolute Error (MAE)


● Root Mean Squared Error (RMSE)




**How to Run**


● Install required libraries:
pip install pandas numpy matplotlib seaborn plotly scikit-learn


● Run the script:
python loan.py




**Future Improvements**


● Use advanced models (Random Forest, XGBoost)


● Build a web dashboard


● Add real-time prediction system


● Improve feature engineering



**Plots Output**

<img width="1920" height="1280" alt="image" src="https://github.com/user-attachments/assets/792a0f51-622b-459c-9d59-8e5a638749f9" />


<img width="1920" height="1280" alt="image" src="https://github.com/user-attachments/assets/c39b24a6-7f96-46ad-a369-0bde130ec065" />


<img width="1920" height="1208" alt="image" src="https://github.com/user-attachments/assets/b3c43349-ed65-455a-a150-7793b20931e3" />



<img width="1920" height="1280" alt="image" src="https://github.com/user-attachments/assets/722dbf07-5d9f-4360-8f2f-37338850ad17" />


<img width="1920" height="1208" alt="image" src="https://github.com/user-attachments/assets/c9400639-c0c8-4143-9ba7-debd62c59883" />


<img width="1920" height="1280" alt="image" src="https://github.com/user-attachments/assets/2cfbfff8-4fa4-4751-b464-7b911d4d2e1f" />


<img width="1920" height="1280" alt="image" src="https://github.com/user-attachments/assets/51c9aad4-a7aa-462b-adc2-54520e7b9f65" />



<img width="1920" height="1280" alt="image" src="https://github.com/user-attachments/assets/3dadb72c-4b12-4259-94ba-d477ba245de3" />
