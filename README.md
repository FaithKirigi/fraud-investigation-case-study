Fraud Investigation Case Study
🔎 Overview

This project simulates a real-world fraud investigation to identify behavioral patterns associated with fraudulent transactions and develop a risk-based detection strategy.

Using transaction data, the analysis uncovers key fraud indicators and translates them into a practical risk scoring system for prioritizing suspicious activity.

🎯 Key Outcomes

Identified high-risk transaction patterns (time, amount, velocity, device trust)
Developed a rule-based risk scoring system to classify transactions
Concentrated 42% of fraud within the high-risk category, improving investigation efficiency
Proposed actionable fraud controls for real-world implementation


📊 Key Insights
Fraud is rare (~1.5%) → requires targeted detection strategies
High-value transactions carry higher fraud risk
Fraud peaks between 00:00–04:00 hours
High transaction velocity is a strong fraud signal
Fraud is driven by behavioral patterns, not demographics


🚨 Fraud Detection Approach
Risk Scoring System

A rule-based scoring model was developed using key fraud indicators:

Transaction amount
Transaction time (high-risk hours)
Transaction velocity
Device trust / behavioral signals

Transactions are classified into:

High Risk → Immediate review / block
Medium Risk → Additional checks
Low Risk → Minimal intervention

This approach improves efficiency by focusing attention on the most suspicious transactions.

🧠 Investigation Approach
Exploratory Data Analysis (EDA)
Fraud pattern identification
Behavioral risk analysis
Risk scoring design


🛠️ Tools & Technologies
Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook

📁 Project Structure
fraud-investigation-case-study
│
├── data
├── notebooks
├── images
├── report
└── README.md


💡 Business Impact

This project demonstrates how data analysis can be translated into practical fraud controls, enabling:

Faster identification of high-risk transactions
Reduced manual review workload
Improved fraud detection efficiency

👩‍💻 Author

Faith Kirigi
Fraud & Risk Analyst
