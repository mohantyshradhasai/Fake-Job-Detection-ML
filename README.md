Fake Job Detection using LSTM

Overview
This project focuses on detecting fraudulent job postings using Natural Language Processing (NLP) and a Deep Learning model (LSTM).  
The model analyzes job-related information such as title, description, company profile, location, and salary to classify whether a job is real or fake.

---

Features
- Combined multiple text features:
  - Job Title  
  - Job Description  
  - Company Profile  
  - Location  
  - Salary Range  
- Text preprocessing:
  - Lowercasing  
  - Removing special characters  
- Exploratory Data Analysis (EDA) using Seaborn  
- Deep Learning model (LSTM) for classification  

---

Approach

 1. Data Preprocessing
- Selected relevant columns  
- Handled missing values using fillna("")  
- Combined multiple columns into one text feature  

 2. Text Cleaning
- Converted text to lowercase  
- Removed special characters  
- Removed extra spaces  

 3. Feature Engineering
- Created a single text column from multiple features  
- Preserved important information like salary and location  

 4. Model Training (LSTM)
- Tokenized text data  
- Applied padding for equal sequence length  
- Built and trained an LSTM model for classification  

 5. Evaluation
- Accuracy, Precision, Recall, F1-score  
- Confusion Matrix  

---

Results
- Achieved high accuracy on test data  
- Dataset is imbalanced (more real jobs than fake jobs)  
- Evaluated model using multiple metrics  

---

Exploratory Data Analysis (EDA)
- Class distribution (real vs fake jobs) using Seaborn  
- Text length comparison  
- Common word patterns in fraudulent job postings  

---

Tech Stack
- Python  
- Pandas, NumPy  
- TensorFlow / Keras (LSTM)  
- Seaborn (Visualization)  

---

How to Run

1. Clone the repository:
git clone https://github.com/mohantyshradhasai/Fake-Job-Detection-ML.git

2. Navigate to the folder:
cd Fake-Job-Detection-ML

3. Install dependencies:
pip install -r requirements.txt

4. Run the project:
python main.py

---

Project Structure
Fake-Job-Detection-ML/
│── data/
│── notebook.ipynb / main.py
│── requirements.txt
│── README.md

---

Note
- Dataset is imbalanced  
- Accuracy alone is not sufficient for evaluation  

---

Future Improvements
- Handle imbalance using SMOTE  
- Try advanced models like BERT  
- Deploy as a web application  

---
Author
Sai Shradha Mohanty  

---

Acknowledgment
This project is built to apply Machine Learning, NLP, and Deep Learning concepts to a real-world problem.

---
