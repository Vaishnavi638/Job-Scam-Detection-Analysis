# Job-Scam-Detection-Analysis ( Python, ML, Power BI)


🔍 Project Overview

This project focuses on identifying and analyzing fraudulent job postings by combining machine learning with data visualization. The goal is to detect scam patterns in job listings and present insights in a clear and interactive way.

📥 Data Collection

- Job posting data was collected from multiple APIs, including:
Adzuna,
Remotive,
RemoteOK,
RapidAPI,

- This resulted in a real-world dataset of 2,661 job postings containing job details such as title, category, description, company information, and application links.

🧹 Data Cleaning & Preprocessing

- Removed irrelevant/unnecessary columns
- Handled missing values appropriately
- Standardized and formatted data for analysis
- Ensured consistency in categorical and binary fields

⚙️ Machine Learning Model

- Used the Fake Job Posting dataset (Kaggle) to train classification models
- Models applied:
          - Logistic Regression
          - Random Forest Classifier
          - XGBoost Classifier
          - Logistic Regression performed best among the models
- The trained model was then used to predict scam probability on the real-world dataset collected from APIs
  
📊 Data Visualization

- An interactive dashboard was created using Microsoft Power BI to present insights derived from the model predictions.
- Dashboard includes:
- Key KPIs (Total Jobs, Scam %, Average Scam Probability)
- Scam vs Non-scam distribution
- Risk level segmentation (High / Medium / Low)
- Analysis by job type and category
- Feature-based insights (suspicious keywords, email presence)
- Top domains associated with scam postings
- Trend analysis over time

📈 Key Insights

- A significant portion of job postings were identified as potentially fraudulent based on model predictions
- Jobs containing suspicious keywords tend to have higher scam probability
- Absence of contact information (such as email) is associated with higher risk
- Risk segmentation helps in prioritizing verification of job postings

🛠 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, LogisticRegression, XGBoost)
- APIs (Adzuna, Remotive, RemoteOK, RapidAPI)
- Microsoft Power BI

🎯 Conclusion

This project demonstrates how machine learning models trained on labeled datasets can be applied to real-world data to detect potential job scams. The integration of analytics and visualization helps convert model outputs into actionable insights for better decision-making.
