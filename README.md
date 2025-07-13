# Customer Classification using Logistic Regression

This project involves applying **Logistic Regression** to the `customers.csv` dataset in order to classify customers based on behavioral or demographic attributes.

## Objective

- Use logistic regression to classify customers into distinct categories (e.g., high vs low spenders).
- Analyze how different features contribute to the classification.
- Evaluate the model using appropriate classification metrics.

## Dataset

**File Name:** customers.csv

The dataset includes variables such as:
- Age
- Annual Income
- Spending Score
- Gender (optional)
- Other demographic or behavioral attributes

A target column (either existing or engineered) is used to define the classes (e.g., binary labels for segmentation).

## Concepts Covered

- Logistic Regression (Binary or Multiclass)
- Data Preprocessing and Feature Selection
- Sigmoid Function and Decision Boundary
- Confusion Matrix and Classification Report
- Accuracy, Precision, Recall, F1-Score

## Workflow Summary

1. Load and explore the dataset.
2. Preprocess the data:
   - Handle missing values
   - Encode categorical variables (if needed)
   - Normalize features
3. Define the target label for classification (e.g., spending class)
4. Train a Logistic Regression model.
5. Evaluate the model using classification metrics.
6. Interpret the model coefficients and results.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

## Conclusion

Logistic regression provides a simple yet effective way to model binary or multiclass classification problems. It helps in identifying the most important features affecting customer behavior and can serve as a baseline for more complex models.

## Author

Shubham Charate  
Machine Learning and Full Stack Developer

## License

This project is licensed under the MIT License.
