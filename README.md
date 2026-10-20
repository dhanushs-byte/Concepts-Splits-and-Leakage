# Concepts-Splits-and-Leakage
## Task 1: Concepts, Splits and Leakage

In this task, I worked with a sample loan-default dataset to understand the basic steps involved in building a machine learning model. I divided the data into training, validation, and testing sets using a 60:20:20 ratio.

I trained decision tree models with different depths and compared their training and validation accuracy to understand how overfitting happens. I also used 5-fold cross-validation with Logistic Regression to check how consistently the model performs.

Next, I demonstrated data leakage by comparing scaling before splitting the data with the correct method of fitting the scaler only on the training data. Finally, I classified four real-world problems as supervised or unsupervised learning and learned the seven main steps of a machine learning workflow.

**Tools used:** Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

**Learning outcome:** I gained practical experience with data splitting, overfitting, cross-validation, data leakage, and the basic machine learning workflow.

# To classify four problems as supervised or unsupervised

| Problem | ML Category | Explanation |
|---|---|---|
| Spam detection | Supervised | Learns from labeled spam and non-spam messages |
| Customer segmentation | Unsupervised | Groups similar customers without predefined labels |
| House price prediction | Supervised | Learns from examples with known house prices |
| Anomaly detection | Unsupervised | Identifies unusual patterns in data |
# Seven-step ML workflow

Define the problem and prediction target.



Collect the dataset.



Explore the data and understand its distributions.



Clean and preprocess the data.



Split into training, validation, and test sets.



Train, validate, and tune models using suitable metrics.



Evaluate the selected model on the test set, then save or deploy it.
