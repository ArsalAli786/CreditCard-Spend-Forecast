# Credit Card Spend Analysis & Forecasting

## 📌 Project Overview
This project analyzes customer credit card spending patterns and forecasts future spending trends using **Facebook Prophet**. The insights can help financial institutions improve budgeting, marketing strategies, and personalized financial services.

## 📊 Key Features
- **Exploratory Data Analysis (EDA)**: Identifying top spending categories, seasonal trends, and customer segmentation.
- **Machine Learning Models**:
  - Anomaly detection using **Isolation Forest**.
  - Customer segmentation using **K-Means & DBSCAN**.
  - Association rule mining using **Apriori & FP-Growth**.
- **Time-Series Forecasting**:
  - Future spending predictions with **Facebook Prophet**.
  - Evaluation using **MAE & RMSE**.
- **Deployment**:
  - **Streamlit Web App** for interactive forecasting and visualization.

## 📂 Dataset Description
The dataset contains transaction details such as:
- **Transaction_ID**: Unique identifier
- **Customer_ID**: Unique customer ID
- **Transaction_Date**: Date of transaction
- **Amount**: Transaction amount
- **Category**: Spending category (Food, Travel, Shopping, etc.)
- **Merchant**: Merchant/store name
- **Location**: City where the transaction occurred
- **Balance_After_Transaction**: Remaining balance

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/credit-card-forecasting.git
cd credit-card-forecasting
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run Data Analysis (Jupyter Notebook)
```bash
jupyter notebook
```
### 4️⃣ Run Streamlit Web App
```bash
streamlit run app.py
```

## 🏆 Results & Insights
- Identified key spending patterns and peak transaction periods.
- Successfully segmented customers based on spending behavior.
- Achieved accurate spending forecasts using **Facebook Prophet**.
- Deployed an interactive **Streamlit app** for real-time analysis.

## 📜 Future Improvements
- Incorporate external factors (inflation, interest rates) into forecasting.
- Enhance anomaly detection for fraudulent transactions.
- Expand customer segmentation for personalized financial recommendations.

## 🤝 Contributing
Feel free to fork this repository, create a branch, and submit a **Pull Request** if you’d like to contribute!

## 📩 Contact
For any questions or collaboration, reach out to me on [LinkedIn](https://www.linkedin.com/in/arsal-ali-311b99221/) or via email at **arsalali687@gmail.com**.

---
**⭐ If you found this project useful, please give it a star!** 🌟
