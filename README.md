# Ml_assignment
### Data Exploration

In the data exploration phase, we use the Iris dataset, which is a well-known dataset for classification tasks. We load the Iris dataset to understand its structure and features. This involves examining the dataset’s contents, such as the types of features it contains and their distributions. This step helps us get familiar with the data before applying any machine learning models.

### Data Splitting

The dataset is split into training and test sets. This split is crucial for evaluating the performance of the machine learning model. Typically, the data is divided so that a portion (e.g., 80%) is used to train the model, while the remaining portion (e.g., 20%) is reserved for testing. This allows us to assess how well the model performs on unseen data and ensures that the model's evaluation is unbiased.

### Linear Regression

In the linear regression phase, we predict salaries based on years of experience using a linear regression model. After training the model on the training data, we make predictions on the test set. We then evaluate the model’s performance using Mean Squared Error (MSE), which measures the average squared difference between the actual and predicted salaries. A lower MSE indicates a better-performing model.