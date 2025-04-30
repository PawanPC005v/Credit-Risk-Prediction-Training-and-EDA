# Credit-Risk-Prediction Using Machine Learning (Accuracy: 97%)

Credit risk assessment is a critical task for financial institutions, helping them evaluate the likelihood of default among potential borrowers. In this project, we apply machine learning techniques—specifically Logistic Regression, XGBoost, and other algorithms—on the American Express dataset to predict credit card defaults. Our objective is to determine the most effective model for this task and identify key predictors of credit risk.

Among the models tested, XGBoost emerged as the top performer, achieving an accuracy of 97.3%, precision of 91%, F1-score of 91%, and AUC score of 92%. While Logistic Regression and other models also produced strong results, they did not surpass the performance of XGBoost. Our analysis reveals that credit score, credit limit utilization, and number of days employed are the most important factors in predicting credit default. Interestingly, borrower age was found to have minimal predictive value.

These findings have practical implications for financial institutions seeking to enhance their credit risk models. By incorporating advanced machine learning algorithms such as XGBoost, institutions can more accurately detect potential defaults and minimize financial losses.

📊 Dataset
This project utilizes data from the "AmExpert 2021 CODELAB - Machine Learning Hackathon", hosted by HackerEarth. The dataset, provided by American Express, includes information relevant to customer credit behavior.

Original dataset: 45,528 rows × 19 columns

Subset used: 30,000 rows × 19 columns

Target variable: credit_card_default (binary: 0 or 1)

Features: 6 categorical and 13 numerical variables

📥 Download the dataset: Kaggle Link

🔍 EDA, Feature Engineering & Modeling
All data processing, exploratory data analysis (EDA), and model training details are documented in our Jupyter notebook.

📘 Access the notebook here:
Credit Risk Analysis Notebook on GitHub

🧪 Model Performance

Model	Accuracy
Logistic Regression	94.64%
Random Forest	96.50%
Decision Tree	96.63%
LightGBM	96.68%
K-Nearest Neighbors	96.81%
CatBoost	96.83%
XGBoost	97.34%

🚀 Future Directions

Future improvements could involve:

Exploring other models like Support Vector Machines (SVMs), Neural Networks, and Deep Learning architectures to evaluate performance across different conditions.

Incorporating alternative data sources—such as social media activity or digital footprints—to enrich prediction models.

Enhancing model interpretability and fairness, especially in high-stakes financial decision-making.

These steps may further improve the accuracy, precision, and robustness of credit risk prediction systems.
