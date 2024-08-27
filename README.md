# Customer Reservation Behavior Analysis and Prediction

## Introduction

This project analyzes and predicts customer reservation behavior using a dataset containing demographic and reservation information. The primary goal is to uncover patterns, perform segmentation, and forecast reservations, cancellations, and completions.

## Dataset

The dataset includes the following features:
- **Customer ID**
- **Age**
- **Gender**
- **Income Level**
- **Country**
- **Reservation Date**
- **Travel Date**
- **Travel Duration**
- **Travel Type** (Business, Vacation, Family, etc.)
- **Travel Destination**
- **Reservation Fee**
- **Reservation Status** (Completed, Cancelled)
- **Customer Satisfaction Score**

## Project Structure

- **Project_Findings.docx**: Detailed analysis, including data exploration, cleaning, segmentation, and model evaluation.
- **notebook-last.ipynb**: Jupyter notebook containing the code for data processing, analysis, and model predictions.
- **Dataset.csv**: The raw data used for analysis.

## Key Findings

### 1. Data Exploration and Cleaning
- No missing or duplicate values in the dataset.
- Date columns were converted to datetime objects.
- Summary statistics revealed key insights into the distribution of numerical and categorical features.

### 2. Data Analysis
- **Correlation Analysis**: Weak or no correlation between numerical features.
- **Gender vs. Reservation Status**: Slightly higher cancellation rates among men, but no significant influence.
- **Income Level vs. Travel Type**: High-income customers prefer adventure travel.

### 3. Segmentation and Customer Profiling
- **K-Means Clustering**: Identified five customer segments with distinct characteristics.
- **GMM Clustering**: Used for more flexible segmentation, highlighting overlapping clusters.

### 4. Predictive Modeling
- **Prophet Model**: Selected as the most reliable model for predicting cancellations and completions.
- **Model Evaluation Metrics**: MAE, MSE, and MAPE were used to evaluate model performance.

## Recommendations

- **Targeted Marketing Campaigns**: Tailor marketing efforts to the identified customer segments.
- **Enhanced Services**: Improve service offerings based on customer profiles to increase satisfaction.
- **Customer Retention Programs**: Implement strategies to reduce cancellation rates and enhance customer loyalty.

## How to Run the Project

1. Clone the repository and navigate to the project directory:
   ```bash
   git clone [repository_link]
   cd project-directory
   ```
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook notebook-last.ipynb
   ```

## Conclusion

This project provides a comprehensive analysis of customer reservation behaviors, offering actionable insights for improving marketing strategies, service delivery, and customer satisfaction. The predictive models implemented here are valuable for anticipating customer actions and optimizing business outcomes.
