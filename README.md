# 📊 Customer Churn Analysis

Understanding why customers leave a service is one of the most important challenges for subscription-based businesses. This project analyzes the **Telco Customer Churn** dataset to uncover patterns behind customer attrition using data analysis, visualization, machine learning, and customer segmentation.

Rather than jumping directly into predictive modeling, the project follows a complete data science workflow—starting with understanding the data, cleaning it, building predictive models, validating their performance, and finally segmenting customers into meaningful business groups.

---

# 🚀 Project Goal

The primary objective of this project is to answer a simple but important business question:

> **Why do customers churn, and how can businesses identify customers who are most likely to leave?**

Using customer demographics, billing information, service usage, and contract details, this project explores the factors influencing customer retention and demonstrates how data-driven insights can support better business decisions.

---

# 📂 Dataset

**Dataset:** Telco Customer Churn

- 👥 7,043 Customer Records
- 📑 33 Features
- 🎯 Target Variable: **Churn Value**

The dataset contains information about:

- Customer demographics
- Contract details
- Internet and phone services
- Payment methods
- Monthly & Total Charges
- Customer Tenure
- Churn Status

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

# 🔄 Project Workflow

The project follows a structured end-to-end data science pipeline.

---

## 📌 Step 1 — Data Collection

The project begins with the **Telco Customer Churn** dataset containing information for more than **7,000 telecom customers**.

The dataset includes customer demographics, subscription details, billing information, service usage, payment methods, contract types, and churn status.

**Objective**

Collect reliable business data that can be analyzed to understand customer behaviour and identify the reasons behind customer churn.

---

## 📌 Step 2 — Exploratory Data Analysis (EDA)

Before building any predictive models, the dataset was explored to understand its structure and uncover hidden patterns.

The analysis included:

- Understanding dataset dimensions and data types
- Checking churn distribution
- Studying customer tenure
- Exploring monthly and total charges
- Comparing churn across contract types
- Analyzing payment methods
- Examining internet service usage
- Correlation analysis
- Statistical summaries
- Cross-tabulation analysis

**Outcome**

EDA provided valuable insights into customer behaviour and established a strong foundation for the machine learning phase.

---

## 📌 Step 3 — Data Cleaning

Real-world datasets often contain inconsistencies that need to be addressed before modeling.

The preprocessing stage involved:

- Converting incorrect data types
- Handling missing values
- Removing unnecessary columns
- Preparing the dataset for machine learning

**Outcome**

A clean, consistent, and machine-learning-ready dataset.

---

## 📌 Step 4 — Feature Selection

Not every feature contributes equally to predicting customer churn.

This step involved:

- Separating features and target variables
- Evaluating feature importance
- Removing low-impact features
- Reducing model complexity while maintaining performance

**Outcome**

A more efficient dataset containing only meaningful predictors.

---

## 📌 Step 5 — Train-Test Split

The dataset was divided into:

- **80% Training Data**
- **20% Testing Data**

This ensures that model performance is evaluated on unseen data, providing a realistic estimate of how well the model generalizes.

---

## 📌 Step 6 — Random Forest Model

Random Forest was selected because of its robustness, ability to handle structured datasets, and strong predictive performance.

Three different approaches were explored:

- Baseline Random Forest
- Random Forest with balanced class weights
- Hyperparameter-tuned Random Forest

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

**Outcome**

A reliable classification model capable of predicting customer churn effectively.

---

## 📌 Step 7 — Cross Validation

To ensure that the model performs consistently across different subsets of data, **5-Fold Cross Validation** was performed.

Instead of relying on a single train-test split, the model was repeatedly trained and validated on different data partitions.

**Outcome**

More reliable performance estimates and improved confidence in the model.

---

## 📌 Step 8 — ROC-AUC Curve

The predictive capability of the model was further evaluated using the **Receiver Operating Characteristic (ROC) Curve** and **Area Under the Curve (AUC)**.

This provides a deeper understanding of how well the model distinguishes between customers who are likely to churn and those who are not.

**Outcome**

A comprehensive evaluation of model performance beyond simple accuracy.

---

## 📌 Step 9 — Customer Segmentation using K-Means

Prediction alone is not enough for business decision-making.

To better understand customer groups, **K-Means Clustering** was applied using:

- Customer Tenure
- Monthly Charges
- Total Charges
- Predicted Churn Probability

The Elbow Method was used to determine the optimal number of clusters.

The resulting customer segments help businesses identify:

- High-risk customers
- Loyal premium customers
- Budget-conscious customers

**Outcome**

Actionable customer segments that support targeted retention strategies and personalized marketing.

---

## 📌 Step 10 — Data Visualization

Throughout the project, various visualizations were created to simplify complex information and communicate findings effectively.

Visualizations include:

- Histograms
- Boxplots
- Countplots
- Correlation Heatmaps
- ROC Curve
- Elbow Curve
- Scatter Plots
- Cluster Visualizations

**Outcome**

Clear visual storytelling that transforms raw data into understandable business insights.

---

# 📈 Key Insights

Some important observations from the analysis include:

- Customers with **month-to-month contracts** are more likely to churn.
- Customers with **shorter tenure** show a higher churn tendency.
- Monthly charges influence customer retention.
- Contract type and payment methods significantly impact churn behaviour.
- Customer segmentation reveals distinct groups with different retention risks.

---

# 🎯 What I Achieved

This project allowed me to experience the complete lifecycle of a real-world data science project—from raw data exploration to predictive modeling and customer segmentation.

Through this project, I was able to:

- Analyze a real telecom dataset containing more than **7,000 customer records**.
- Perform comprehensive Exploratory Data Analysis (EDA).
- Clean and preprocess raw business data.
- Select meaningful features for predictive modeling.
- Build multiple Random Forest classification models.
- Evaluate model performance using Cross Validation and ROC-AUC analysis.
- Segment customers using K-Means clustering.
- Create informative visualizations that communicate business insights clearly.
- Strengthen my understanding of practical machine learning and business analytics.

### 💡 Biggest Learning

One of the most valuable lessons from this project was realizing that successful machine learning begins long before model training.

Understanding the data, asking the right questions, cleaning inconsistencies, and interpreting business problems are just as important as building accurate predictive models.

---

# 📁 Project Structure

```
Customer-Churn-Analysis/
│
├── Customer_Churn_Analysis.ipynb
├── Telco_customer_churn.xlsx
├── README.md
```

---

# ▶️ Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-analysis.git
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

Run the notebook sequentially in **Google Colab** or **Jupyter Notebook**.

---

# 🌱 Future Improvements

This project can be extended further by:

- Comparing multiple machine learning algorithms
- Automating feature engineering
- Building interactive dashboards using Power BI or Tableau
- Deploying the model as a web application
- Creating an API for real-time churn prediction
- Integrating business recommendation systems

---

# 🤝 Contributing

Contributions, suggestions, and feedback are always welcome. Feel free to fork this repository, open an issue, or submit a pull request.

---

# 📜 License

This project is developed for educational and learning purposes.
