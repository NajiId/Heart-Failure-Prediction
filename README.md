# EDA Explore Data Analytics

This project explores a dataset using various data analytics techniques.

## Dataset Overview
The dataset contains information related to heart disease, with the following columns.

## Data Exploration
- Loaded dataset .
- Checked the first few rows of the dataset using `data.head()`.
- Checked the shape of the dataset using `data.shape`.
- Described the dataset using `data.describe().T`.
- Checked for missing values using `data.isnull().sum()`.
- Plotted a heatmap to visualize missing values using `sns.heatmap()`.
- Checked for duplicate rows using `data.duplicated().sum()`.

## Analysis
- Checked the count of heart disease cases using .
- Plotted histograms for various features using `data.hist()` to understand their distributions.
- Plotted a correlation matrix using `sns.heatmap()` to identify relationships between features.

## Data Processing
- Encoded categorical variables using `LabelEncoder`.
- Combined encoded categorical variables and numerical variables into a single DataFrame.
- Split the dataset into training and testing sets using `train_test_split`.

## Model Building and Evaluation
- Trained multiple classification models including KNeighborsClassifier, DecisionTreeClassifier, GaussianNB, SVC, RandomForestClassifier, and GradientBoostingClassifier.
- Evaluated each model's performance using confusion matrix and classification report.
- Plotted a barplot to compare the accuracy of different classifiers.

## Additional Task: GridSearchCV
- Used GridSearchCV to find the best hyperparameters for RandomForestRegressor.
- Evaluated the best model's performance on the test set.
