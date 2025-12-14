# ⏱️ Customer Complaint Resolution Time Prediction

## 📌 Project Overview
**Customer Complaint Resolution Time Prediction** is a machine learning project that predicts the expected time (in hours) required to resolve customer complaints using **Natural Language Processing (NLP)** and **Regression techniques**.  
Customer complaints are often written in free-text form and contain rich contextual information about issue type, urgency, and severity. By analyzing this unstructured text, the model estimates resolution time, helping organizations **prioritize tickets, improve SLA compliance, and optimize resource allocation**.

---

## 🎯 Project Objective
The primary goals of this project are to:

- Analyze unstructured customer complaint text using NLP  
- Transform textual data into meaningful numerical features  
- Train a regression model to predict complaint resolution time  
- Evaluate model performance using standard regression metrics  
- Provide an interactive way for users to estimate resolution time for new complaints  

---

## 🧠 Problem Statement
Manual prioritization of customer complaints is time-consuming and subjective. Delays in identifying high-effort complaints can lead to SLA violations and poor customer satisfaction.  
This project automates the estimation of complaint resolution time, enabling **data-driven decision-making** in customer support operations.

---

## 🧹 Data Preprocessing & Cleaning
Text preprocessing was a critical step to ensure high-quality feature extraction. The following steps were applied:

- Removal of special characters, numbers, and unnecessary symbols using **Regular Expressions (Regex)**  
- Stopword removal using **NLTK** to reduce noise  
- Conversion of text to lowercase for uniformity  
- General text normalization to improve model consistency  

These steps helped convert raw complaint narratives into clean and analyzable text.

---

## 🔍 Feature Extraction
To transform textual data into numerical form, the project uses:

- **TF-IDF Vectorization (Term Frequency–Inverse Document Frequency)**  
  - Captures the importance of words relative to the entire complaint dataset  
  - Reduces the influence of commonly occurring but less informative words  
  - Enables the regression model to learn meaningful text patterns  

---

## 🤖 Model Training (Regression)
- A **Linear Regression** model was trained to learn the relationship between complaint text features and their corresponding resolution times  
- The model predicts continuous values (resolution time in hours), making it suitable for SLA forecasting and workload planning  

---

## 📊 Model Evaluation
The model performance was evaluated using:

- **Mean Absolute Error (MAE)** – Measures average prediction error in hours  
- **R² Score** – Indicates how well the model explains variance in resolution time  

These metrics ensure the model is both interpretable and practically useful.

---

## 🧑‍💻 User Interaction (Bonus Feature)
An interactive feature was added that allows users to:

- Enter a custom complaint description  
- Instantly receive a **predicted resolution time**  

This simulates a real-world customer support tool and enhances the project’s practical value.

---

## 🛠️ Technologies & Libraries Used
- **Python** – Core programming language  
- **Pandas & NumPy** – Data handling and numerical operations  
- **NLTK** – Text preprocessing and stopword removal  
- **Scikit-learn** – TF-IDF vectorization, regression modeling, and evaluation  
- **Regex** – Text cleaning and normalization  

---

## 💡 Key Insights & Impact
- Text-based complaints carry strong signals related to resolution complexity  
- NLP-driven regression can significantly assist in **ticket prioritization**  
- The approach supports **SLA optimization, workload balancing, and faster response planning**  
- Demonstrates practical application of NLP in real-world business problems  

---

📌 *This project showcases skills in NLP, regression modeling, feature engineering, and building end-to-end ML pipelines—making it ideal for data analyst, ML engineer, and RevOps-focused roles.*
