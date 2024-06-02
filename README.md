# Linear Regression Health Costs Calculator


# 1.Curriculum Development and Additional Resources:
Interactive instructional content for the machine learning curriculum is under development.

For now, utilize video challenges in the certification.

Supplement your learning with additional resources, similar to real-world project scenarios.

# 2.Project Objective:
The challenge involves predicting healthcare costs using a regression algorithm.

You will be given a dataset with various information about individuals, including their healthcare costs.

Use this dataset to predict healthcare costs for new data.

# 3.Data Preparation:
The first two cells of the notebook import necessary libraries and the dataset.

Convert categorical data to numerical values.

Split the dataset into two parts: 80% for training (train_dataset) and 20% for testing (test_dataset).

Separate the "expenses" column to create train_labels and test_labels.

# 4. Model Training and Evaluation:
Create and train a model using the train_dataset and train_labels.

Run the final cell in the notebook to evaluate the model's performance on the test_dataset.

To pass, the model must achieve a Mean Absolute Error (MAE) of under 3500, indicating predictions within $3500 of actual healthcare costs.

The final cell will also graph the predicted expenses versus actual expenses using the test_dataset.
