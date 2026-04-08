🎓 XGBoost for Student Performance Prediction

This project focuses on predicting student academic performance using behavioral data and machine learning techniques. We implement and evaluate an XGBoost model to understand how different factors influence student outcomes and to assess the predictive power of data-driven approaches.

📥 1. Import and Study Data

In this section, we:

Load the dataset from Kaggle
Merge the two available tables into a single dataset
Explore the data by checking its dimensions
Handle missing values by removing empty entries

This step ensures that the dataset is clean, consistent, and ready for modeling.

🔀 2. Data Split

Here, we:

Separate the dataset into features (X) and target variable (y)
Split the data into training (train_data) and testing (test_data) sets

This allows us to train the model on one portion of the data and evaluate its performance on unseen data.

🤖 3. Model Development

In this section, we:

Use scikit-learn and XGBoost libraries
Build and train the model using key hyperparameters such as:
n_estimators
learning_rate
max_depth

We experiment with these parameters to improve model performance and achieve better predictions.

📊 4. Model Evaluation

To evaluate the model, we compute:

Mean Squared Error (MSE) 📉
R (correlation coefficient) 📈
Accuracy ✅

These metrics help us understand how well the model performs and how close the predictions are to the actual values.

📈 5. Data Visualization

Finally, we visualize the results by:

Displaying a table with feature importance 🧠
Plotting a graph comparing real vs predicted values 📊

These visualizations provide insights into which variables are most influential and how accurate the model predictions are.
