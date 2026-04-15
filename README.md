# 💳 Credit Card Fraud Detection — Machine Learning Project

A Machine Learning project that detects fraudulent credit card transactions using classification techniques.  
The model is trained on transaction data and handles class imbalance using undersampling.

---

## 🚀 Features

- Detects fraudulent vs legitimate transactions  
- Handles highly imbalanced dataset  
- Data preprocessing and missing value handling  
- Uses undersampling to balance data  
- Logistic Regression model implementation  
- Model evaluation using accuracy score  

---

## 📂 Dataset

- Contains transaction details with anonymized features (`V1` to `V28`)  
- Includes:
  - Time  
  - Amount  
  - Class (Target)  
- **Target Variable:**
  - `0` → Legitimate  
  - `1` → Fraud  

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Checked and handled missing values  
- Converted target column to integer type  

### 2. Data Analysis
- Explored class distribution (highly imbalanced dataset)  
- Compared statistics of fraud vs legit transactions  

### 3. Handling Imbalance
- Applied **undersampling**  
- Created balanced dataset using equal fraud and legit samples  

### 4. Model Training
- Algorithm used: Logistic Regression  
- Split data into training and testing sets  

### 5. Model Evaluation
- Evaluated using accuracy score  
- Compared training and test performance  

---

## 🛠️ Tech Stack

- Python  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  

---

## ▶️ Run Locally

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install numpy pandas matplotlib seaborn scikit-learn
python main.py
