Customer_Segmentation using KMeans Clustering Algorithm

This project applies unsupervised and supervised machine learning techniques to perform customer segmentation and identify high-spending customers using behavioral and demographic data.

Dataset:

->The dataset contains anonymized customer information, including:

->Demographics (age, income, family size, etc.)

->Shopping behavior (recency, total amount spent)

->Lifestyle factors (marital status, education, device type)

Project Objectives:

->Segment customers into distinct groups using K-Means clustering.

->Visualize customer clusters using PCA.

->Classify high-value customers using a Random Forest Classifier.

->Generate actionable insights for marketing and targeting.

Key Features & Methods:

Data Preprocessing:

->Removed irrelevant columns like Customer_ID, Customer_Since

->Imputed missing values using median

->Encoded categorical features (LabelEncoder and get_dummies)

Feature Engineering:

->Total_kids = Kids_Home + Teens_Home

->Income_per_person = Annual_Income / (Family_Size + 1)

EDA (Exploratory Data Analysis):

->Histograms, boxplots to understand distribution and outliers

->Spending patterns by membership tier

Clustering (Unsupervised Learning):

->Scaled data using StandardScaler

->Applied K-Means Clustering (n=4)

->Visualized clusters using PCA

Classification (Supervised Learning):

->Defined High Spenders (above median total spent)

->Trained a Random Forest Classifier

->Evaluated using classification report and confusion matrix

Libraries Used:

->pandas, numpy, matplotlib, seaborn

->sklearn: KMeans, PCA, LabelEncoder, StandardScaler, RandomForestClassifier

->Google Colab environment

Outputs:

->customer_segmented_output_improved.csv — enriched dataset with cluster and spender labels

Visual plots of:

->Spending distributions

->Clusters in 2D PCA space

->Confusion matrix for high spender classification
