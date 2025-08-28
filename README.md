# Churn-Data-Analysis
This project analyzes customer churn data to understand the factors influencing customer retention and attrition. The analysis is performed using Python with libraries such as ** NumPy, Pandas, Matplotlib, and Seaborn in a Jupyter Notebook**.

# Objective:
The main objective of this project is to explore customer churn patterns and provide insights that can help businesses reduce churn and improve customer retention.
Technologies & Libraries Used

**Python Libraries :**
```
1. NumPy → Numerical operations

2. Pandas → Data manipulation and preprocessing

3. Matplotlib → Data visualization

4. Seaborn → Statistical data visualization

```

**Key Visualizations :**
```
1. Count of Customers by Churn:
Shows the distribution of churned vs. non-churned customers.
Result: Out of the total customers, 5174 did not churn while 1869 churned.

2. Services vs. Churn (Multiple Categories):
Compares churn distribution across different services such as PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, and StreamingMovies.

3. Percentage of Churned Customers:
Pie chart representing the percentage split of churned vs. non-churned customers.
Result: ~26.54% of customers churned, while ~73.46% stayed.
```

**Insights:**
Churn Rate: Around 26.54%, which is a significant proportion.
Service-Based Churn: Customers using certain internet services (e.g., fiber optic) showed higher churn compared to DSL.
Retention Focus: Improving customer support, online security, and backup services may help reduce churn

**How to Run the Project :**
1. Clone this repository:
git clone https://github.com/your-username/churn-analysis.git
cd churn-analysis

2. Install dependencies:
pip install numpy pandas matplotlib seaborn jupyter

3. Run the Jupyter Notebook:
jupyter notebook "Churn Analysis.ipynb"

**Conclusion:**
This analysis highlights the importance of understanding customer behavior and service usage patterns in predicting churn. By leveraging these insights, companies can build strategies to enhance customer satisfaction and reduce churn rates.
