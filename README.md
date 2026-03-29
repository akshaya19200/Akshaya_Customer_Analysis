Title : Industry-Oriented Customer Behavior Analysis for Business Decision Making

RISE Internship — Data Science & Analytics | Tamizan Skills


Student Details:

| Field | Details |

| Name | Akshaya |
| Internship | RISE Internship |
| Domain | Data Science & Analytics |
| Organization | Tamizhan Skills |


Project Overview:

Companies collect large volumes of customer data but struggle to convert it into actionable insights. This project analyzes real-world customer data and generates insights that help businesses improve customer retention, targeting, and overall strategy.


Tools and Technologies:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


Dataset:

| Column | Description |

| CustomerID | Unique Customer ID |
| Gender | Male or Female |
| Age | Age of Customer |
| Annual Income (k$) | Yearly Income in thousands |
| Spending Score (1-100) | Customer Spending Behavior |


Project Steps:

Step 1 — Data Ingestion

- Loaded dataset using Pandas read_csv
- Checked shape and first 10 rows

Step 2 — Data Cleaning

- Checked null values and duplicates
- Filled missing values with median
- Verified data types and statistics

Step 3 — Exploratory Data Analysis

- Age Distribution
- Gender Distribution
- Income Distribution
- Spending Score Distribution
- Boxplots for Gender vs Income
- Boxplots for Gender vs Spending Score
- Scatter Plot Income vs Spending Score
- Correlation Heatmap

Step 4 — Customer Segmentation

- Used Elbow Method to find optimal K
- Applied KMeans Clustering with 5 clusters
- Plotted clusters with centroids
- Generated cluster summary table

Step 5 — Behavior Pattern Identification

- Identified High Value customers
- Identified Low Value customers
- Based on Income and Spending Score

Step 6 — Predictive Analysis

- Logistic Regression Model
- Random Forest Classifier
- Compared accuracy of both models
- Plotted Confusion Matrix
- Plotted Feature Importance chart

Step 7 — Visualization

- All outputs visualized using
- Matplotlib and Seaborn

Step 8 — Business Insight Report

- Summarized all key findings
- Provided business recommendations


Cluster Summary:

| Cluster | Label | Description |

| 0 | VIP | High Income and High Spending |
| 1 | Impulsive | Low Income and High Spending |
| 2 | Standard | Medium Income and Medium Spending |
| 3 | Careful | High Income and Low Spending |
| 4 | Budget | Low Income and Low Spending |


Business Recommendations:

- Retain VIP customers with loyalty rewards
- Target Careful customers with premium ads
- Offer discounts to Budget segment customers
- Monitor Impulsive customers for churn risk
- Use Spending Score as primary KPI


How to Run:

Step 1 - Install Libraries

pip install pandas numpy matplotlib seaborn scikit-learn

Step 2 — Place Dataset

Place store_customers.csv in same folder as notebook

Step 3 
    jupyter notebook

Step 4 
    Open Akshaya_Customer_Analysis.ipynb

Step 5 
    Click Cell and then Run All


Folder Structure:

Akshaya_Customer_Analysis/
│
├── Akshaya_Customer_Analysis.ipynb
├── store_customers.csv
├── README.md
└── Screenshots/
    ├── 01_Age_Distribution.png
    ├── 02_Gender_Distribution.png
    ├── 03_Income_Distribution.png
    ├── 04_Spending_Score.png
    ├── 05_Boxplot_Income.png
    ├── 06_Boxplot_Spending.png
    ├── 07_Scatter_Plot.png
    ├── 08_Correlation_Heatmap.png
    ├── 09_Elbow_Method.png
    ├── 10_Customer_Segmentation.png
    ├── 11_HighValue_LowValue.png
    ├── 12_Confusion_Matrix.png
    ├── 13_Feature_Importance.png
    └── 14_Business_Report.png


Expected Outcomes:

- Hands-on experience with real business datasets
- Strong data analytics portfolio project
- Understanding of data-driven decision making
- Job relevance for Data Analyst and Data Scientist roles

Contact:

Organization : Tamizan Skills
Website : www.tamizhanskills.com
Email : Rise@tamizhanskills.com