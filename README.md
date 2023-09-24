# Employee Attrition Predict Project

## Introduction:

I had the opportunity to participate in the Kaggle competition titled "Binary Classification with a Tabular Employee Attrition Dataset.

This competition focused on predicting employee attrition based on a tabular dataset containing various employee-related features. It provided an exciting challenge to develop and fine-tune machine learning models to help organizations understand and mitigate the risk of employee turnover.

Participating in Kaggle competitions like this one allows data scientists and machine learning practitioners to sharpen their skills, learn from the global data science community, and tackle complex real-world problems. It's a valuable opportunity for professional development and networking with like-minded individuals passionate about data analysis and predictive modeling.

![image](https://github.com/zcxads/ASAC_ML_Project/assets/96506354/7f1dcb9a-885a-4f04-bb45-62f7d5c0d8ce)


## Dataset Description
The dataset contains the following features:

- Education: Highest level of education attained by the individual.
- Education Field: Field or area of study for the individual's education.
- Marital Status: Marital status of the individual.
- Num Companies Worked: Number of companies the individual has worked for.
- Total Working Years: Total number of years the individual has worked in their career.

- Employee Number: Unique identification number for each employee.
- Training Time Last Year: Number of hours of training the employee received in the last year.
- Years at Company: Number of years the employee has been with the current company.
- Years in Current Role: Number of years the employee has been in their current role.
- Years since last Promotion: Number of years since the employee's last promotion.

- Daily Rate: The daily pay rate or salary of the employee.
- Hourly Rate: The hourly pay rate or salary of the employee.
- Monthly Income: The monthly income or salary of the employee.
- Monthly Rate: A monthly rate or salary-related metric.
- Stock Option Level: Level of stock options granted to the employee.
- Percent Salary Hike: The percentage increase in salary or wage.

- Department: The department within the company where the employee works.
- Business Travel: Frequency or nature of business-related travel undertaken by the employee.
- Distance from Home: The distance between the employee's home and the workplace.
- Job Level (1~5): The level or rank of the employee's job within the company (typically ranging from 1 to 5).
- Overtime: Whether the employee works overtime or not.
- Performance Rating: The employee's performance rating.
- Years with Current Manager: The number of years the employee has worked under the current manager.

- Environment Satisfaction: The level of satisfaction the employee has with their work environment.
- Job Involvement: The degree to which the employee is involved and engaged in their job.
- Job Satisfaction: The overall satisfaction the employee feels with their job.
- Relationship Satisfaction: The satisfaction level in terms of work-related relationships.
- Work-Life Balance: How balanced the employee perceives their work and personal life.

## Methodology
Our approach to solving this binary classification problem involves the following steps:

1. Data Preprocessing:

- Handle missing values (if any): Begin by identifying and addressing missing values in the dataset. This may involve imputing missing values with appropriate techniques like mean, median, or mode, or removing rows or columns with significant missing data.

- Encode categorical variables: Categorical variables (e.g., "Education Field," "Gender") need to be converted into numerical format for machine learning algorithms to process. Common encoding methods include one-hot encoding, where each category becomes a binary column, or label encoding, where categories are replaced with integer labels.

- Split the dataset into training and testing sets: To assess the model's performance, divide the dataset into two subsets: a training set (typically 80% of the data) used to train the model and a testing set (remaining 20%) used to evaluate its performance. This separation ensures that the model's accuracy can be tested on unseen data.

2. Feature Selection and Engineering:

- Analyze feature importance: Utilize techniques like feature importance scores from tree-based models (e.g., Random Forest), correlation analysis, or domain knowledge to determine which features are most relevant for predicting employee attrition. Features with high importance are retained for modeling.

- Create new features if needed: If domain knowledge suggests that certain combinations of existing features or new derived features could improve predictive power, engineer these new features. This might involve mathematical operations or aggregations of existing variables.

3. Model Selection:

- Choose appropriate binary classification algorithms: Select suitable machine learning algorithms for binary classification. Common choices include Logistic Regression, Random Forest, Gradient Boosting (e.g., XGBoost, LightGBM), Support Vector Machines (SVM), and Neural Networks, among others. The choice should consider the dataset size, complexity, and interpretability requirements.
Model Training:

- Train the selected models on the training dataset: Fit the chosen classification models to the training data. The models learn patterns and relationships between input features and the target variable (employee attrition) during this training phase.

- Perform hyperparameter tuning: Optimize the model's performance by adjusting hyperparameters (e.g., learning rates, tree depths, regularization parameters) through techniques like grid search or random search. This process fine-tunes the model's behavior.

4. Model Evaluation:

- Evaluate model performance: Use appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and ROC AUC to assess how well the model performs on the testing dataset. These metrics provide insights into the model's ability to correctly classify employees as churners or non-churners.

- Use confusion matrices: Create confusion matrices to gain a deeper understanding of model predictions. This helps in identifying false positives, false negatives, true positives, and true negatives, which can inform decision-making.

5. Model Interpretation:

Interpret the model results: Analyze the model's coefficients (for linear models like Logistic Regression) or feature importances (for tree-based models) to understand which factors contribute the most to employee attrition predictions. This interpretation can offer valuable insights for HR and management.

## Conclusion
By following these steps, we aim to develop a robust binary classification model that can accurately predict employee attrition. This model can be valuable for HR departments and organizations to proactively address attrition-related issues and improve employee retention.
