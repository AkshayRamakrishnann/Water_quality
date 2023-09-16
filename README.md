# Water_quality

![image](https://github.com/AkshayRamakrishnann/Water_quality/assets/111365771/76052995-d974-491a-b359-1fa1487620ea)


## Data Preprocessing

In this section, we performed data preprocessing to prepare the dataset for model training. Here are the key steps:

- Loaded the dataset from a CSV file using the Pandas library.
- Checked the shape of the dataset to understand its size (number of rows and columns).
- Investigated and handled missing values by dropping rows with any missing data.
- Visualized the distribution of the target variable, 'Potability,' using a pie chart and observed that the dataset is imbalanced.
- Balanced the dataset by upsampling the minority class (Potability = 1) to create a balanced dataset.

## Exploratory Data Analysis (EDA)

We visualized the correlation between different features in the dataset using a heatmap. This helped us understand the relationships between variables and identify potential patterns.

![image](https://github.com/AkshayRamakrishnann/Water_quality/assets/111365771/5ceffb20-d36a-46f2-b110-ae86307d3622)


## Model Building

### Logistic Regression

We imported the LogisticRegression model from scikit-learn and trained it on the training data. After training, we calculated the accuracy of the model on the testing data. The accuracy achieved by the Logistic Regression model was approximately 86.45%.

### Gaussian Naive Bayes

Next, we imported the Gaussian Naive Bayes model from scikit-learn and trained it on the training data. We then calculated the accuracy of the model on the testing data, which yielded an accuracy of around 60.83%.

### Decision Tree Classifier

We also imported the DecisionTreeClassifier model from scikit-learn and trained it on the training data. The accuracy of the Decision Tree Classifier model on the testing data was approximately 80.83%.

## Model Comparison

To compare the accuracies of the different models, we created a bar plot. The plot shows the accuracy achieved by each model: Logistic Regression (86.45%), Gaussian Naive Bayes (60.83%), and Decision Tree Classifier (80.83%).

![image](https://github.com/AkshayRamakrishnann/Water_quality/assets/111365771/2e919722-737c-4317-9a3a-546f9055a4f4)


The results indicate that the Logistic Regression model outperforms the other models in terms of accuracy on this dataset.

Thank you for exploring this machine learning project. If you have any questions or would like to delve deeper into the code and analysis, please feel free to reach out.


