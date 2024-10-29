# Loan Approval Prediction

## Project Overview
This project focuses on predicting an applicant’s eligibility for a loan based on various personal and financial factors such as income, education, work experience, previous loans, and more. The goal is to develop a machine learning model that classifies applicants as eligible or ineligible for loan approval.

### Key Features:
- **Data Visualization:** An exploratory data analysis phase showcasing applicant demographics, income levels, loan details, and correlations. 
- **Machine Learning Model with Gradio Interface:** A Logistic Regression model was trained to make loan approval predictions based on the input features. A Gradio interface provides an interactive prediction tool, allowing users to input features and get predictions.

---

## Project Structure

- **`data/`**: Contains the raw dataset (`loan_data.csv`).
- **`notebooks/`**: Jupyter notebooks for data preprocessing, visualization, and model training.
- **`scripts/`**: Python scripts for data transformation and model training.
- **`README.md`**: Project documentation.

---

## Data Visualization

### Overview
In-depth visualizations were created to explore and understand the dataset, helping identify patterns that can impact loan eligibility, such as income levels, credit history, and demographic details.

### Visualization Highlights
- **Applicant Demographics:** Plots showing distributions across genders, marital status, and property areas.
- **Income and Loan Amount Relationships:** Visual analyses showing how applicant and co-applicant incomes relate to requested loan amounts.
- **Loan Status Distributions:** Visual summaries of loan approval rates across different factors, highlighting trends within the dataset.

<div style="height: 500px; overflow-y: scroll;">
  <img src="https://github.com/user-attachments/assets/3e47b355-1dce-4d5c-9327-89a8b716be2d" alt="Data Visualization" style="display: block; margin: 0 auto; width: 00%;">
</div>


## Model Training

### Approach
We used a Logistic Regression model for classification and evaluated the model’s performance with metrics including:
- **Accuracy**
- **Recall**
- **Precision**
- **F1-Score**
- **ROC-AUC Score**

### Model Evaluation
The trained model achieved the following results:
- **Accuracy:** 81.82%
- **Recall:** 100%
- **Precision:** 80%
- **F1-Score:** 88.89%
- **Mean Square Error (MSE):** 0.1818

---

## Loan Prediction Application

A Gradio interface was developed for interactive loan eligibility predictions. Users can input applicant details, such as gender, marital status, income, and other relevant factors, and receive a real-time prediction of their loan approval probability.

### Features of the Gradio App
- **Client Attributes Input:** Options to specify the applicant’s demographic and financial details.
- **Predict Button:** Provides the likelihood of loan approval.
- **Loan Propensity Display:** Outputs the probability of loan approval in a user-friendly interface.


https://github.com/user-attachments/assets/0973b88c-2ffe-40e4-bd7c-3e7e93026320



---

## Getting Started

### Prerequisites
- **Python 3.8+**
- **Required Packages**: `pandas`, `seaborn`, `matplotlib`, `scikit-learn`, `gradio`, `numpy`

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/loan-approval-prediction.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
---

## Usage

1. Launch the Gradio app and input applicant features in the designated fields.
2. Press the **Prediction Button**.
3. View the loan approval probability under **Client’s Loan Propensity**.

---

## Results and Conclusion

The project provides a foundational model for loan approval prediction with an easy-to-use interface. Further improvements could include additional model tuning, inclusion of more diverse datasets, and integration with real-time financial APIs to enhance prediction accuracy.


