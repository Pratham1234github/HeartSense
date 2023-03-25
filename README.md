# HEART_DISEASE-PROJECT

The aim of this project is to predict whether a person has heart disease or not based on their medical attributes. Heart disease is a common and serious health issue that affects millions of people worldwide. Early detection and accurate diagnosis are crucial for effective treatment and management of the disease.

To achieve this, we will use machine learning techniques and data analysis to build a predictive model that can accurately classify individuals into two groups: those with heart disease and those without it. The dataset we will use is the Cleveland Heart Disease dataset, which contains 303 instances and 14 attributes, including demographic, clinical, and laboratory measurements.

The project will involve the following steps:

**Data Exploration and Preparation:**
We will start by exploring the dataset, analyzing the distribution of each attribute, checking for missing values, and cleaning the data if necessary. We will also perform feature selection to identify the most relevant attributes that contribute to the prediction of heart disease.

**Data Visualization:**
Visualizing the data is an important step to gain insights and identify patterns that can help us understand the relationships between the attributes and the target variable. We will use various visualization techniques, including scatter plots, histograms, and correlation matrices.

**Model Selection and Training:**
We will evaluate several machine learning algorithms, including logistic regression, decision tree, random forest, and support vector machines, to determine the best-performing model. We will train the model on the training set and evaluate its performance on the test set using various metrics, including accuracy, precision, recall, and F1 score.

**Hyperparameter Tuning:**
We will fine-tune the hyperparameters of the selected model using techniques such as grid search and cross-validation to improve its performance and prevent overfitting.

**Model Evaluation and Interpretation:**
We will evaluate the final model's performance on the test set and interpret its predictions to identify the most important features that contribute to the prediction of heart disease.

The output of this project will be a machine learning model that can predict heart disease with high accuracy and identify the most important features that contribute to the prediction. This model can be used by healthcare professionals to aid in the diagnosis and treatment of heart disease, ultimately improving patient outcomes.


**ABOUT THE DATASET USED HERE**
The original data came from the Cleavland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/heart+Disease

also one version is available on kaggle https://archive.ics.uci.edu/ml/datasets/heart+Disease

Data Dictionary

age: Displays the age of the individual.

sex: Displays the gender of the individual using the following format : 1 = male 0 = female

cp- Chest-pain type: displays the type of chest-pain experienced by the individual using the following format : 0 = typical angina 1 = atypical angina 2 = non — anginal pain 3 = asymptotic

trestbps- Resting Blood Pressure: displays the resting blood pressure value of an individual in mmHg (unit). anything above 130-140 is typically cause for concern.

chol- Serum Cholestrol: displays the serum cholesterol in mg/dl (unit)

fbs- Fasting Blood Sugar: compares the fasting blood sugar value of an individual with 120mg/dl. If fasting blood sugar > 120mg/dl then : 1 (true) else : 0 (false) '>126' mg/dL signals diabetes

restecg- Resting ECG : displays resting electrocardiographic results 0 = normal 1 = having ST-T wave abnormality 2 = left ventricular hyperthrophy

thalach- Max heart rate achieved : displays the max heart rate achieved by an individual.

exang- Exercise induced angina : 1 = yes 0 = no

oldpeak- ST depression induced by exercise relative to rest: displays the value which is an integer or float.

slope- Slope of the peak exercise ST segment : 0 = upsloping: better heart rate with excercise (uncommon) 1 = flat: minimal change (typical healthy heart) 2 = downsloping: signs of unhealthy heart

ca- Number of major vessels (0–3) colored by flourosopy : displays the value as integer or float.

thal : Displays the thalassemia : 1,3 = normal 6 = fixed defect 7 = reversible defect: no proper blood movement when excercising

target : Displays whether the individual is suffering from heart disease or not : 1 = yes 0 = no
