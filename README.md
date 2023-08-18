#  ExploreEdge Attrition Model


### Building a predictive model for forecasting attrition risk and proposing data-driven strategies to reduce employee turnover at ExploreEdge.

##### Problem Definition and Data Collection:
The key to success in any organization is attracting and retaining top talent. The goal of this repo is to identify the key factors contributing to the attrition of employees. The data is pseudo-randomly generated using Python code and Synthesized using Generative Adversive Networks. The dataset contains #### rows.


Data Preview

![image](https://github.com/ShaunMoloi/Attrition/assets/34385762/56cb6151-84d7-49a0-8fdc-211e19c5e207)

The Python notebook will:
### 1. Data Preprocessing and Exploration
Exploratory Data Analysis will be conducted to identify the key factors contributing to attrition, visualize and analyze the data to uncover patterns, correlations, and potential insights. Data cleaning: Handle missing values, outliers, and inconsistencies in the dataset.
### 2. Feature selection & engineering: 
Identify and select relevant features that are likely to impact attrition. Create new features based on domain knowledge, such as tenure, job role scores, and employee rating indices.
### 3. Data Splitting
Split the dataset into training and testing sets: Using 80% portion of the data for model training and the rest for evaluation. 
### 4. Model Selection, Training and Evalution:
A comprehensive evaluation of various machine learning algorithms was conducted to determine the optimal algorithm for the attrition model. For the development of the attrition model for ExploreEdge, a selection of powerful machine learning libraries was employed. The scikit-learn library provided a versatile foundation, with LogisticRegression, DecisionTreeClassifier, RandomForestClassifier, KNeighborsClassifier, and SVC chosen strategically to harness their respective capabilities. LogisticRegression was utilized for crafting a precise logistic regression model, while DecisionTreeClassifier enabled the construction of a decision tree classifier capable of intricate pattern recognition. RandomForestClassifier further enhanced the model's predictive accuracy through an ensemble of decision trees. KNeighborsClassifier was employed to leverage the k-nearest neighbors approach for efficient data classification. Additionally, the use of SVC facilitated the creation of a support vector classifier, enabling the exploration of complex decision boundaries for accurate attrition prediction. This ensemble of libraries underscores the commitment to crafting a robust and adaptable attrition model tailored to ExploreEdge's specific requirements.
The selection process involved assessing each algorithm's performance metrics, including accuracy, precision, recall, F1-score, and area under the curve.
### 5. Feature Importance Analysis:
Identify important features: Analyze feature importance scores to understand which factors contribute the most to attrition predictions.
Strategy Proposal

## Insights discovered
Dataset attributes
<img width="273" alt="image" src="https://github.com/ShaunMoloi/Attrition/assets/34385762/3abcabec-d4ef-40ab-b84e-6e958c1c7921">

ExploreEdge consists of 795 Employees with an average age of 37 years old. 
Distribution of WorkModels of the Employees:

Remote                221
High-flex Hybrid      206
Medium-flex Hybrid    154
Fully office based    109
Fully Remote           80
Low - flex hybrid      20
Field - Force           5
Name: WorkModel, dtype: int64

## Insights gathered from the Exploratory Data Analysis: 
Attrition is more common among individuals who work only in the office. ExploreEdge Bank, Marketing Sales & Distribution, and other departments all contribute to this. Married and single people are more likely to depart the firm. Employees operating at a lower level within their employment position may be more likely to contemplate leaving.

Key Attributes that contribute to attrition are:
WorkModel, ExploreEdge Bank, Marriage Status, Job Level. 

Do note that the Model is currently working in progress as data constraints limit modeling capacity. Results are currently overfitting.
i.e. ![image](https://github.com/ShaunMoloi/Attrition/assets/34385762/4ef00567-c3d2-4f31-9988-8202540c9e7d)

Do note that with limited data, I applied an approach of using Generate Real-World Synthetic Data with CTGAN
 










Exploratory Data Analysis will be conducted to identify the key factors contributing to attrition, build a predictive model to
forecast attrition risk, and propose data-driven strategies to reduce employee turnover.

 build a predictive model to
forecast attrition risk, and propose data-driven strategies to reduce employee turnover.
The analysis will involve exploring various HR and employee-related data to gain insights that
can be used to make informed decisions and improve employee retention.
The primary objective of this case study is to provide a recommendation that will assist ExploreEdge in predicting employee attrition and addressing/derisking by providing data-driven insights and recommendations based on the analysis of historical employee data.


Recommendations:

Long Service Awards, Best Performer,
look at manager
Acquire external data: Consider external factors that may influence attrition, such as industry trends, economic conditions, and competitive job market data.
Assumptions:
Attrition Occurs on the last day of the monthx    

# Inisights 
Save on space.. moving forwards.. hire more and give remote workers. 
Researh on benefits

Key Tools and Libraries to be used:
• Gitlib, GitHub,Python, R, PowerBi
