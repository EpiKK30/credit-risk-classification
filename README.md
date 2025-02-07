# Credit Risk Classification Project

## Overview

The Credit Risk Classification Project aims to assess and classify the creditworthiness of borrowers based on historical lending data. By employing various machine learning techniques, including logistic regression, we evaluate the likelihood of a loan being high-risk or healthy. This analysis helps financial institutions make informed lending decisions.

## Repository Structure

- **Credit_Risk**
  - `credit_risk_classification.ipynb`: Jupyter Notebook containing the data analysis and model implementation.
  - `lending_data.csv`: The dataset containing historical lending activity.
  - `README.md`: This documentation.

## Data Preparation

1. **Data Loading:**
   - The `lending_data.csv` file was loaded into a Pandas DataFrame.

2. **Feature and Label Selection:**
   - The "loan_status" column was designated as the label (`y`), where 0 indicates a healthy loan and 1 indicates a high-risk loan.
   - The remaining columns were used as features (`X`).

3. **Data Splitting:**
   - The dataset was split into training and testing sets using `train_test_split` from scikit-learn.

## Model Implementation

### Logistic Regression

1. **Model Training:**
   - A logistic regression model was trained using the training data (`X_train` and `y_train`).

2. **Predictions:**
   - Predictions were made on the testing data (`X_test`) using the trained model.

3. **Model Evaluation:**
   - The model's performance was evaluated using a confusion matrix and classification report.

## Results

- **Accuracy Score:** [Provide the accuracy score]
- **Precision Score:** [Provide the precision score]
- **Recall Score:** [Provide the recall score]

**Model Performance Summary:**
The logistic regression model demonstrated [strong/moderate/weak] ability to classify loans as high-risk or healthy. The model's accuracy, precision, and recall scores indicate [brief analysis of performance]. 

## Conclusion

Based on the results, the logistic regression model [is/is not] recommended for deployment in predicting loan risk. The model [provides a good balance between precision and recall/has limitations in certain aspects], making it [suitable/unsuitable] for practical use by financial institutions.

## Challenges and Limitations

- **Data Quality:** The dataset had certain limitations which may affect the model's predictions.
- **Model Limitations:** Logistic regression, while effective, may not capture complex non-linear relationships in the data.

## Future Work

Future iterations of this project could explore more advanced models such as decision trees or neural networks to improve predictive accuracy. Additionally, incorporating more features and data points could enhance model performance.

## Getting Started

To replicate the analysis, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   ```

2. **Install the Required Libraries:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**
   Open `credit_risk_classification.ipynb` in Jupyter Notebook to explore the analysis and results.

## References

Data for this project was generated by edX Boot Camps LLC for educational purposes. 

This README provides a comprehensive overview of the Credit Risk Classification project, detailing the steps taken in data preparation, model implementation, evaluation, and recommendations for future work. The project demonstrates the practical application of logistic regression in financial risk assessment.
