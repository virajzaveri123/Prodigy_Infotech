# Prodigy_Infotech
TASK-1
I analyzed a dataset using Python's Pandas and Matplotlib libraries to visualize the distribution of regions. The dataset contains information about population totals in different countries. By plotting a bar chart, I highlighted the frequency of each region. The x-axis represents the regions, and the y-axis represents the count. The width and spacing of the bars were adjusted for clarity.
The resulting chart provides an insightful overview of the distribution of regions based on the dataset.

TASK-2
I conducted EDA on the Titanic dataset, utilizing Python's Pandas, NumPy, Matplotlib, and Seaborn libraries. The dataset contains information about passengers aboard the Titanic, including their demographics, cabin details, and survival outcomes.
The code performs the following steps:
1. Loading the dataset and displaying the initial rows.
2. Checking for missing values and filling them with appropriate values.
3. Converting categorical variables into numerical representations.
4. Handling outliers in the 'Age' and 'Fare' columns.
5. Performing feature engineering by extracting deck information from the 'Cabin' column and creating additional columns.
6. Binning the 'Age' column into age groups.
7. Conducting EDA by visualizing survival counts, survival by class, age distribution, fare distribution, survival by age, survival by family relationships, and survival by title.
8. Calculating and visualizing survival rates by class, sex, and age group.
9. Calculating the correlation matrix and visualizing it as a heatmap.

TASK-3
I implemented a decision tree classifier using the Scikit-Learn library in Python to predict whether customers will subscribe to a bank deposit ("depo_yes") based on various features.
The code performs the following steps:
1. Loading the dataset from a CSV file and preprocessing it, including handling missing values by filling them with the mean and encoding categorical variables.
2. Splitting the data into training and testing sets.
3. Training the decision tree classifier on the training set.
4. Making predictions on the testing set and evaluating the model's performance using classification metrics.
5. Visualizing the decision tree using matplotlib and tree.plot_tree().
6. Determining feature importance by calculating the feature importances and sorting them in descending order.
7. Performing hyperparameter tuning using grid search to find the best combination of hyperparameters for the decision tree classifier.
8. Rebuilding the decision tree classifier using the best hyperparameters and evaluating its performance.
The code showcases the decision tree model's ability to make predictions and provides insights into the most important features for predicting customer subscriptions.
