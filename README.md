
# Credit-Risk-Analysis-using-ml

Accurately predicting the Probability of Default (PD) is essential for effective credit risk management. This project leverages the German Credit dataset from Kaggle to develop machine learning models that estimate PD, enabling financial institutions to identify high-risk borrowers and make more informed lending decisions.

## Objective

To build robust predictive models that assess the likelihood of loan default using real-world credit data, thereby enhancing decision-making and reducing potential financial losses.

## Dataset

- **Source:** [German Credit Data – Kaggle](https://www.kaggle.com/datasets/uciml/german-credit)
- **Attributes:** Includes over 11 features such as credit amount, loan duration, age, employment status, and loan purpose.
- **Target Variable:** Indicates whether a customer is a good or bad credit risk.

## Core Concepts

- **Probability of Default (PD):** The likelihood that a borrower fails to meet their debt obligations.
- **Expected Loss Formula:**  
  **Expected Loss = PD × EAD × LGD**  
  *(This project focuses specifically on PD.)*

## Tools & Technologies

- Python
- pandas, NumPy for data manipulation
- Scikit-learn for modeling
- Matplotlib, Seaborn for visualization
- Jupyter Notebook for development

## Methodology

1.Data Cleaning & Preprocessing

2.Exploratory Data Analysis (EDA)

3.Model Training 

4.Performance Evaluation 

5.Result Interpretation and Insights
## Outcome

The final model effectively distinguishes between high and low-risk applicants, demonstrating strong predictive capability and offering valuable insights for risk mitigation.

## Future Directions

- Incorporate additional datasets for greater generalizability  
- Experiment with ensemble and deep learning methods  
- Extend to full Expected Loss modeling by including EAD and LGD estimation

