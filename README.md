# Sales-Intelligence-and-Forecasting-System

## Overview
This project focuses on performing **data analysis, visualization, and predictive modeling** using the classic Northwind dataset. It incorporates **clustering, regression, and classification techniques** to drive meaningful business insights such as customer segmentation, sales forecasting, and churn prediction.

---

## Dataset
Data is derived from Northwind's relational structure including:
- `category.csv`
- `customers.csv`
- `employees.csv`
- `orders.csv`
- `order_details.csv`
- `products.csv`
- `shipping.csv`

---

## Technologies Used
- **Python**: Pandas, NumPy, Seaborn, Matplotlib
- **Scikit-learn**: KMeans, Linear Regression, Logistic Regression
- **Power BI**: For Dashboarding

---

## Key Features

### 1. Customer Segmentation using K-Means Clustering
- Feature engineering: total spending, average order value, order frequency, preferred product category.
- Applied OneHotEncoding and StandardScaler for preprocessing.
- Implemented KMeans clustering to group customers by behavior.
- Visualized clusters using scatter plots and pair plots.

### 2. Sales Prediction using Linear Regression
- Engineered features such as discount percentage and order date components.
- Trained a linear regression model to forecast total sales.
- Evaluated using MAE, MSE, and R² metrics.
- Plotted actual vs. predicted values and residuals.
- Included user input interface for real-time prediction.

### 3. Customer Churn Prediction using Logistic Regression
- Defined churn as customers inactive for 6+ months.
- Engineered features related to customer activity and value.
- Trained a logistic regression model and evaluated with:
  - Accuracy
  - Confusion Matrix
  - ROC Curve
  - Classification Report
- Interactive input-based churn prediction supported.

---

## Power BI Dashboard
Created a Power BI dashboard for visual storytelling, highlighting:
- Regional sales trends
- Product-wise performance
- Key customer behavior insights

---

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/northwind-ml-project.git
    ```
2. Place the CSV files in the correct directory
3. Open and run the `.ipynb` or `.py` scripts in Jupyter or Colab
4. Open the `.pbix` file in Power BI Desktop to view the dashboard

---

## Outcomes
- Identified customer segments for targeted marketing
- Built models to **predict future sales** and **identify churn risk**
- Developed visual dashboards to inform data-driven decisions

---

## Author
**Rohit Tiwari**

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/rohit-tiwari-data/) or view more projects on my [GitHub](https://github.com/RohitTiwari7879).

---

> _This project demonstrates the application of machine learning and data visualization in real-world business contexts using retail datasets._
