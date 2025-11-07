Customer Returns Prediction in E-Commerce Using Machine Learning

📌 Project Overview
This project predicts customer return behavior in e-commerce using machine learning techniques on the **UCI Online Retail II (2010–2011)** dataset.  
The objective is to help businesses minimize return rates and enhance customer satisfaction.

📊 Dataset
- **Source:** UCI Machine Learning Repository – Online Retail II (2010–2011)
- Link - https://archive.ics.uci.edu/dataset/502/online+retail+ii
- **Size:** 500,000+ transactions
- **Features:** Invoice, Quantity, Price, Customer ID, Country, InvoiceDate

⚙️ Methodology
1. Data Cleaning and Preprocessing  
2. Feature Engineering (TotalPrice, Invoice Frequency, etc.)  
3. Model Building – Logistic Regression, Random Forest, XGBoost  
4. Evaluation using Accuracy, AUC, and Confusion Matrices  
5. Visualization using Tableau Dashboard

🚀 Results
| Model | Accuracy | AUC |
|--------|-----------|-----|
| Logistic Regression | **0.91** | 0.89 |
| XGBoost | 0.90 | **0.93** |
| Random Forest | 0.88 | 0.91 |

- Logistic Regression achieved the highest accuracy.  
- XGBoost recorded the highest AUC.  

📈 Dashboard
Developed an interactive Tableau dashboard with:
- Return Rate by Country  
- Sales vs Returns Overview  
- Model Performance Comparison  
- Feature Importance Visualization

🧰 Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn, Tableau

📂 Files
- `customerreturnsfinal.ipynb` – ML Implementation  
- `customerreturnsfinal.twb` – Tableau Dashboard  
- `README.md` – Documentation

Author
**Sarah Tondle**

⭐ If you find this project useful, feel free to fork and star the repository!
