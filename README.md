# 📊 Telecom Churn Analysis

## 🧠 Objective

An end-to-end churn analysis project using SQL for data exploration, Python for machine learning-based prediction, and Power BI for interactive visualization.

---

## 🛠 Tools & Technologies

| Stage              | Tools Used                           |
|--------------------|---------------------------------------|
| Source Data        | Excel                                 |
| Data Exploration   | SQL Server (via SSMS)                 |
| Data Modeling      | Python (Jupyter Notebook, scikit-learn) |
| ETL                | SQL Server → Power BI (Summary Page) + Python → CSV → Power BI (Prediction Page) |
| Visualization      | Power BI                              |

---

## 🔄 Project Workflow

1. **Data Loading**
   - Imported raw Excel dataset into SQL Server.

2. **Data Exploration & Transformation (SQL)**
   - Performed EDA, filtering, and transformation using SQL queries in SSMS.
   - Created SQL views specifically for churn prediction.

3. **ETL Process**
   - **Summary Page**:  
     - SQL Server connected to Power BI using import method.
   - **Prediction Page**:  
     - Transformed SQL data was exported to excel.
     - Python Random Forest model trained on this data.
     - Prediction output saved as CSV and loaded into Power BI.

4. **Churn Prediction (Python)**
   - Random Forest model trained using scikit-learn.
   - Predictions exported for dashboard use.

5. **Power BI Dashboard**
   - Two-page interactive dashboard:
     - **Churn Summary Page** (live SQL Server connection)
     - **Churn Prediction Page** (CSV from Python model)
   - Navigation added between views for seamless user experience.

---

## 📈 Model Performance

| Metric       | Value   |
|--------------|---------|
| Algorithm    | Random Forest Classifier |
| Accuracy     | ~85%    |
| Key Features | Tenure, Contract Type, Monthly Charges |

---

### 💬 Feedback & Contributions

I welcome feedback, suggestions, or collaboration ideas to improve this project or explore similar analyses.  
If you’ve found this useful or have any input, feel free to:

- ⭐ Star this repo  
- 📬 Create an issue or submit a pull request  
- 🗨️ Reach out directly via contact info below

---

### 📬 Contact

**Laksh Saronja**  
_Data Analyst | SQL • Python • Power BI_  
📧 Email: [lakshsaronja014@gmail.com](mailto:lakshsaronja014@gmail.com)   
🌐 GitHub: [github.com/lakshsaronja014](https://github.com/lakshsaronja014) 
📄 [LinkedIn Profile](https://www.linkedin.com/in/laksh-saronja?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) 


