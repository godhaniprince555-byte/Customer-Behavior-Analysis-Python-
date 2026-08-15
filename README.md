# E-Commerce Customer Behavior Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on e-commerce customer data to understand customer behavior, engagement patterns, purchasing activity, and factors associated with customer churn.

The analysis uses Python-based data analysis and visualization techniques to clean the dataset, explore customer interactions, identify patterns, and generate meaningful insights from customer activity data.

## 🎯 Objectives

* Analyze e-commerce customer behavior and engagement.
* Understand customer interaction across desktop and mobile/app platforms.
* Examine purchasing and transaction patterns.
* Analyze customer engagement with products, promotions, and wishlists.
* Investigate customer service interactions and churn.
* Identify relationships and patterns between customer behavior variables.
* Prepare clean and structured data for further analytics.

## 📊 Dataset

The dataset contains customer-level e-commerce behavior information, including:

* Account Length
* Location Code
* User ID
* Credit Card Information Saved
* Push Notification Status
* Add to Wishlist
* Desktop Sessions
* App Sessions
* Desktop Transactions
* Total Product Detail Views
* Session Duration
* Promotion Clicks
* Average Order Value
* Sale Product Views
* Discount Rate per Visited Products
* Product Detail Views per App Session
* App Transactions
* Add to Cart per Session
* Customer Service Calls
* Churn

The notebook loads the data from `Customer_Behavior_Data.csv` using Pandas.

## 🛠️ Technologies & Tools

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical analysis
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Plotly** – Interactive visualization
* **Jupyter Notebook**

## 🔍 Analysis Process

### 1. Data Loading

The customer behavior dataset is imported using Pandas and initially inspected to understand its structure and variables.

### 2. Data Cleaning

The analysis follows a structured EDA process that includes:

* Reviewing column names and meanings
* Standardizing column names
* Converting columns to appropriate data types
* Checking and handling missing values
* Checking for duplicate records
* Identifying potential outliers
* Exploring relationships between variables

The notebook reports that duplicate rows were checked, missing values were handled, and data types were converted successfully.

### 3. Exploratory Data Analysis

The project explores different dimensions of customer behavior, including:

* Customer sessions and activity
* Desktop vs. app engagement
* Product detail views
* Promotion interactions
* Wishlist activity
* Add-to-cart behavior
* Transaction activity
* Average order value
* Discount behavior
* Customer service calls
* Customer churn

Visualizations are used throughout the analysis to make behavioral patterns easier to interpret.

## 📈 Key Business Areas Explored

### Customer Engagement

Analyzes customer sessions, product views, session duration, wishlist activity, and add-to-cart behavior to understand how customers interact with the e-commerce platform.

### Purchasing Behavior

Examines transactions, average order value, and product interactions to understand purchasing activity and customer value.

### Marketing Engagement

Explores promotion clicks, sale product views, discounts, and push notification status to understand customer response to promotional activities.

### Customer Churn

The dataset includes a `churn` variable, allowing customer activity and engagement patterns to be examined in relation to churn behavior.

## 💡 Business Value

This analysis can help an e-commerce business:

* Understand customer engagement patterns
* Identify differences between app and desktop behavior
* Improve promotional strategies
* Understand purchasing behavior
* Identify potential churn indicators
* Improve customer retention strategies
* Support data-driven marketing decisions

## 📂 Project Structure

```text
Customer-Behavior-Analysis/
│
├── Customer Behavior Analysis.ipynb
├── Customer_Behavior_Data.csv
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository.

2. Make sure Python is installed.

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

4. Place `Customer_Behavior_Data.csv` in the same directory as the notebook.

5. Open Jupyter Notebook:

```bash
jupyter notebook
```

6. Open:

```text
Customer Behavior Analysis.ipynb
```

7. Run the notebook cells sequentially.

## 📌 Skills Demonstrated

* Exploratory Data Analysis
* Data Cleaning
* Data Preprocessing
* Customer Behavior Analytics
* E-Commerce Analytics
* Data Visualization
* Statistical Analysis
* Python Programming
* Pandas & NumPy
* Business Insights

## 👤 Author

**Prince Godhani**

This project demonstrates practical experience in using Python and data analytics techniques to transform customer behavior data into actionable business insights.

