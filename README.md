# 🛡️ Fake Job Detection using LSTM

## 📌 Overview
With the rapid growth of online job platforms, fraudulent job postings have become a serious concern.  
This project aims to detect fake job listings using **Natural Language Processing (NLP)** and a **Deep Learning model (LSTM)**.

The model analyzes multiple job-related features such as **job title, description, company profile, location, and salary** to classify whether a job posting is **Real** or **Fake**.

---

## 🚀 Features
- Combines multiple job attributes into a single input:
  - Job Title  
  - Job Description  
  - Company Profile  
  - Location  
  - Salary Range  
- Text preprocessing pipeline:
  - Lowercasing  
  - Removing special characters  
  - Cleaning extra spaces  
- Exploratory Data Analysis (EDA) using Seaborn  
- Deep Learning-based classification using LSTM  
- Evaluation using multiple performance metrics  

---

## 🧠 Methodology

### 🔹 1. Data Preprocessing
- Selected relevant columns from dataset  
- Handled missing values using `fillna("")`  
- Merged multiple text fields into one feature  

### 🔹 2. Text Cleaning
- Converted text to lowercase  
- Removed special characters and noise  
- Standardized spacing  

### 🔹 3. Feature Engineering
- Combined all important job-related features into a single text column  
- Preserved contextual information like salary and location  

### 🔹 4. Model Building (LSTM)
- Tokenized textual data  
- Applied sequence padding for uniform input length  
- Built and trained an **LSTM (Long Short-Term Memory)** model for classification  

### 🔹 5. Model Evaluation
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---
## 📂 Project Structure
Fake-Job-Detection-ML/
│── data/                # Dataset files
│── notebook.ipynb       # EDA and experimentation
│── main.py              # Model training and execution
│── requirements.txt     # Dependencies
│── README.md            # Documentation
---

## 📊 Results
- Achieved strong performance on test data  
- Model effectively distinguishes between real and fake job postings  
- Dataset is **imbalanced**, with more real jobs than fake ones  
- Used multiple metrics to ensure reliable evaluation  

---

## 📈 Exploratory Data Analysis (EDA)
- Visualized class distribution (Real vs Fake jobs)  
- Analyzed text length variations  
- Identified common patterns in fraudulent postings  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:**  
  - Pandas, NumPy  
  - TensorFlow / Keras (LSTM)  
  - Seaborn (Data Visualization)  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/mohantyshradhasai/Fake-Job-Detection-ML.git
cd Fake-Job-Detection-ML
