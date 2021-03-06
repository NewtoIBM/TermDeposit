# EqQ4EgPVNxQk7HBU

<b>Goal(s):</b>

Predict if the customer will subscribe (yes/no) to a term deposit (variable y)

<b>Data Description:</b>

The data comes from direct marketing efforts of a European banking institution. The marketing campaign involves making a phone call to a customer, often multiple times to ensure a product subscription, in this case a term deposit. Term deposits are usually short-term deposits with maturities ranging from one month to a few years. The customer must understand when buying a term deposit that they can withdraw their funds only after the term ends. All customer information that might reveal personal information is removed due to privacy concerns.

Attributes:

age : age of customer (numeric)

job : type of job (categorical)

marital : marital status (categorical)

education (categorical)

default: has credit in default? (binary)

balance: average yearly balance, in euros (numeric)

housing: has a housing loan? (binary)

loan: has personal loan? (binary)

contact: contact communication type (categorical)

day: last contact day of the month (numeric)

month: last contact month of year (categorical)

duration: last contact duration, in seconds (numeric)

campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

Output (desired target):

y - has the client subscribed to a term deposit? (binary)

# Table of Contents

1 Introduction.

2 Exploration.

3 Preprocessing Data for a Model.

4  LGBMClassifier.

5  Confusion_matrix.

6  RandomForestClassifier.

7 Model Evaluation.

8 Features Importances.

9 Unsupervised Clustering Kmeans. 

10 PCA Dimension Reduction.

11 SHAP Analysis for Exploring Important Features to Explore What Makes Customers to Subscribe.

12 Conclusion.
