German Credit Data Classification 

Overview 

This project uses machine learning techniques to classify credit risk (good/bad) using the Statlog German Credit Data dataset. The objective is to predict whether a person poses a good or bad credit risk based on 24 numerical attributes. 


--- 

Dataset 

Source: UCI Machine Learning Repository – German Credit Data 

File Used: german.data-numeric 

Instances: 1000 

Attributes: 24 numeric attributes per instance 



--- 

Technologies Used 

Python 

Jupyter Notebook 

Scikit-learn 

Pandas, NumPy 

Seaborn, Matplotlib 



--- 

Modeling Approach 

1. Data Preprocessing and Loading 


2. Splitting data into training and test sets 


3. Training and evaluating two models: 

Logistic Regression 

Decision Tree Classifier 





--- 

Results 

Replace 75.5% and 71.5% with your actual accuracy scores 


--- 

Confusion Matrix Visualization 

Used seaborn.heatmap to visualize confusion matrices for both models to evaluate true positives, false positives, etc. 


--- 

Conclusion 

Logistic Regression performed slightly better in terms of accuracy. 

Future work can include: 

Feature scaling 

Hyperparameter tuning 

Trying advanced models like Random Forest or XGBoost 




--- 

How to Run 

1. Clone the repository: 

git clone https://github.com/OnkarSoni90/german-credit-classifier.git 


2. Navigate to the folder and open a.ipynb using Jupyter or VS Code. 


3. Run all cells sequentially. 




--- 

Model Export 

Trained model is saved as: 

german_credit_model.pkl 

Can be loaded for deployment or further analysis. 


--- 

Author 

Onkar Soni 

CSI Portal Task – Celebal Tech# German-Credit-Data-Classification
