📓 Notebook Preview

👉 [View Full Notebook](https://nbviewer.org/github/Khushinkm15/healthcare_readmission_prediction/blob/main/HEALTHCARE%20READMISSION%20DATA.ipynb)

🏥 Healthcare Readmission Prediction



📌 Project Overview



This project focuses on predicting **30-day hospital readmissions** for diabetes patients using machine learning.



The goal is to identify high-risk patients early and enable healthcare providers to take preventive actions, reducing costs and improving patient outcomes.



📊 Dataset



* Source: Diabetes 130-US Hospitals Dataset (1999–2000)
* Total Records: 101,766
* Features Used: 18 clinical and demographic variables



🚀 Project Pipeline



* &#x20;Data Cleaning \& Preprocessing
* &#x20;Exploratory Data Analysis (EDA)
* &#x20;Feature Engineering
* &#x20;Model Building \& Evaluation
* &#x20;Risk Stratification
* &#x20;Business Impact Analysis



🔍 **Key Insights**



📈 Readmission Statistics



* 30-day readmission rate: 11.16%
* Total readmissions: 11,357
* Majority patients: Elderly (65+ years)



⚠️ Major Risk Factors



* &#x20;Previous inpatient admissions
* &#x20;High emergency department visits
* &#x20;Circulatory \& respiratory conditions
* &#x20;Age above 70



🤖 Model Performance (Random Forest)



* Accuracy: 75.53%
* Precision: 19.48%
* Recall: 38.09%
* F1 Score: 25.78%
* ROC-AUC: 0.6529



📌 Model captures \~38% of actual readmissions



📊 Confusion Matrix



True Negatives: 14,508

False Positives: 3,575

False Negatives: 1,406 ⚠️

True Positives: 865



💡 Business Impact (Hypothetical)



Assumptions:

Cost per readmission: $15,000

Intervention cost: $1,000

Effectiveness: 70%



Results:

Patients targeted: 4,440

Readmissions prevented: 606

Net Savings: $4.64 Million



👥 Risk Stratification



| Risk Level     | Patients | Readmission Rate |

| -------------- | -------- | ---------------- |

| Low Risk       | 3,070    | 4.9%             |

| Medium Risk    | 12,844   | 9.8%             |

| High Risk      | 4,175    | 18.1%            |

| Very High Risk | 265      | 41.5%            |



🛠️ Tech Stack



Language: Python

Libraries: pandas, NumPy, scikit-learn, matplotlib, seaborn

Model: Random Forest, Logistic Regression



📂 Project Structure



healthcare-readmission-prediction/

│

├── diabetic\_data.csv

├── diabetic\_data\_cleaned.csv

├── HEALTHCARE READMISSION DATA.ipynb"

├── EXECUTIVE\_SUMMARY.txt

├── requirements.txt

│

└── visualisations/

&#x20;   ├── 01\_target\_distribution.png

&#x20;   ├── 02\_numeric\_distributions.png

&#x20;   ├── 03\_categorical\_distributions.png

&#x20;   ├── 04\_numeric\_vs\_readmission.png

&#x20;   ├── 05\_categorical\_vs\_readmission.png

&#x20;   ├── 06\_correlation\_matrix.png

&#x20;   ├── 07\_model\_comparison.png

&#x20;   ├── 08\_confusion\_matrices.png

&#x20;   ├── 09\_feature\_importance.png

&#x20;   ├── 10\_probability\_distribution.png

&#x20;   ├── 11\_risk\_stratification.png

&#x20;   └── 12\_FINAL\_DASHBOARD.png



🎯 Conclusion



This project demonstrates how machine learning can:



Identify high-risk patients

Reduce hospital readmissions

Generate significant cost savings







