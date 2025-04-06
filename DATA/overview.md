# 📂 Justice-AI Dataset

This is the dataset used in the **Justice-AI** project, which aims to build an AI-based system to prioritize court cases based on multiple real-world factors like severity, urgency, public impact, media attention, and evidence strength.

---

## 📊 Dataset Overview

| Column Name           | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| `case_id`             | Unique identifier for each case (e.g., C001, C002)                          |
| `case_type`           | Type of case (e.g., Rape, Murder, Theft, etc.)                              |
| `victims_count`       | Number of victims involved in the case                                      |
| `severity_level`      | Severity of the case: Low, Medium, High                                     |
| `urgency_level`       | Urgency of resolution: Low, Medium, High                                    |
| `public_impact_level` | Impact on society: Low, Medium, High                                        |
| `date_filed`          | Date the case was filed                                                     |
| `media_attention`     | Whether the case received media attention (True/False)                      |
| `evidence_available`  | Whether strong evidence is available (True/False)                           |
| `status`              | Current case status: Pending, Under Trial, or Closed                        |
| `region`              | Location where the case was filed (e.g., Delhi, Mumbai)                     |
| `priority_score`      | (Currently empty) To be calculated based on the Justice-AI ranking system   |

---

## 🚀 Use Cases

This dataset can be used for:
- Exploratory Data Analysis (EDA)
- Data Visualization
- Building machine learning models for case prioritization
- AI ethics, legal tech research, and fairness analysis

---

## 📌 Note

This dataset is **fictional** but built to reflect the real-world challenges in court case prioritization for research and educational purposes.
