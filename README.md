# 🌐 EasyVisa: Visa Approval Prediction using Machine Learning

![Visa Image](https://tse2.mm.bing.net/th/id/OIP.xDuVe7t90DDqF5nXXwz6FAHaEK?pid=Api\&P=0\&h=180)

## 📌 Project Overview

**EasyVisa** is a machine learning project designed to streamline the U.S. employer-sponsored visa certification process. With the increasing demand for skilled foreign labor, automating the visa approval prediction process can help both employers and government agencies save time, reduce processing errors, and retain high-potential candidates.

---

## 🎯 Objective

* Predict whether a visa application will be **Certified** or **Denied**.
* Minimize the risk of **losing candidates who are likely to be certified**.
* Recommend high-certification-probability profiles to employers for focused processing.

---

## 🧠 Problem Context

* The Office of Foreign Labor Certification (OFLC) processes thousands of employer-sponsored visa applications each year.
* Employers want early predictions to better plan hiring.
* Government agencies want support tools to ensure efficiency, consistency, and fairness in decision-making.

---

## 📂 Dataset Description

| Feature                 | Description                              |
| ----------------------- | ---------------------------------------- |
| `case_id`               | Unique ID of application                 |
| `continent`             | Continent of the employee                |
| `education_of_employee` | Education level                          |
| `has_job_experience`    | Prior job experience (Y/N)               |
| `requires_job_training` | Requires training (Y/N)                  |
| `no_of_employees`       | Number of employees at the employer      |
| `yr_of_estab`           | Year of employer establishment           |
| `region_of_employment`  | U.S. job location                        |
| `prevailing_wage`       | Standard wage for the job                |
| `unit_of_wage`          | Wage unit (Hour, Week, Month, Year)      |
| `full_time_position`    | Full-time position (Y/N)                 |
| `case_status`           | **Target Variable** – Certified / Denied |

---

## 🧰 Technologies Used

* **Python**
* **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
* **Scikit-learn**
* **XGBoost**, **LightGBM**, **CatBoost**, **RandomForest**
* **SMOTE**, **SHAP**
* **Google Colab / Jupyter Notebook**

---

## ⚙️ ML Pipeline

1. **Data Ingestion, Cleaning, Preprocessing and Feature engineering**

   * Categorical encoding
   * Normalization of wage units
2. **Exploratory Data Analysis**

   * Target imbalance
   * Feature relationships
3. **Class Imbalance Handling**

   * SMOTE, oversampling, undersampling
4. **Model Training**

   * XGBoost, CatBoost, LightGBM, RandomForest, AdaBoost
5. **Model Evaluation**

   * Accuracy, Precision, Recall, F1-score
   * Threshold tuning for business priority on recall
6. **Feature Importance**

   * Model-based importances
   * SHAP explainability

---

## 📈 Key Results

* Achieved high **recall** to reduce risk of rejecting likely successful candidates.
* Identified key drivers of approval such as:

  * Education level
  * Job experience
  * Full-time role
  * Wage offered (after unit normalization)
* Improved explainability using **SHAP** for trust and transparency.

---

## 💼 Business Use Cases

* 🔍 Early identification of high-certification candidates
* 📊 Strategic advisory to employers (e.g., on wages and experience)
* 🧾 Policy refinement based on data-driven insights
* 🤝 Human-in-the-loop decision support with confidence scores and feature explanations

---

## 🚀 Getting Started

### Run the notebook:

Open `EasyVisa_VaishnaviHP.ipynb` in **Google Colab** or **Jupyter Notebook**.

---

## 🤝 Contributors

* **Vaishnavi Palyam** – Data Scientist | Developer | Data Engineer

---

## 📬 Contact

For queries, feedback, or collaborations:
**Email:** \[[your-email@example.com](mailto:vaishnavihpde@example.com)]
**LinkedIn:** \[[Your LinkedIn URL](https://www.linkedin.com/in/vaishnavi-palyam-a190952ab/)]


