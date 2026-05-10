# Employee Salary Prediction Using Machine Learning

A machine learning project that predicts whether an employee earns more 
or less than $50K annually based on demographic and employment features. 
Built during IBM SkillsBuild Virtual Internship (2024).

## Problem Statement

Predict binary salary classification (>50K or <=50K) from employee 
attributes using supervised machine learning and deep learning approaches.

## Dataset

- **Size:** 9,406 samples after preprocessing
- **Features:** Age, Workclass, Education, Marital Status, Occupation, 
  Relationship, and more
- **Target:** Binary classification — earns >50K or <=50K

## Models Built & Results

| Model | Accuracy | Weighted F1 |
|-------|----------|-------------|
| XGBoost | **86.88%** | **0.87** |
| Deep Learning (TensorFlow/Keras) | ~83% | - |

### XGBoost Classification Report
- Precision: 0.90 (class 0), 0.77 (class 1)
- Recall: 0.93 (class 0), 0.67 (class 1)
- F1-Score: 0.91 (class 0), 0.72 (class 1)

## Pipeline

1. Data Collection & Exploration
2. Outlier Detection & Removal
3. Data Preprocessing & Feature Engineering
4. Model Training & Hyperparameter Tuning
5. Model Evaluation & Benchmarking
6. GUI Deployment for Real-time Prediction

## Tech Stack

- **Language:** Python
- **ML Libraries:** Scikit-learn, XGBoost, TensorFlow, Keras
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib
- **Deployment:** Interactive GUI for real-time salary prediction

## Key Features

- Compared multiple preprocessing variants with XGBoost
- Built and trained a deep learning model with TensorFlow/Keras
- Visualized training vs validation accuracy across epochs
- Deployed interactive GUI — input employee details, get instant 
  salary prediction with confidence score

## How to Run

```bash
git clone https://github.com/Bluestar0000/EMPLOYEE-SALARY-PREDICTION-USING-MACHINE-LEARNING.git
cd EMPLOYEE-SALARY-PREDICTION-USING-MACHINE-LEARNING
jupyter notebook MACHINE_LEARNING_PROJECT.ipynb
```

## Results



![Confusion Matrix](<img width="652" height="334" alt="Screenshot 2025-07-23 003405" src="https://github.com/user-attachments/assets/c3510d6d-e9cf-49c2-818a-9a4df2c8ca65" />
)




![Training Accuracy](<img width="642" height="465" alt="Screenshot 2025-07-23 003605" src="https://github.com/user-attachments/assets/94e48463-c5f3-4907-9a7a-12433ca481f0" />
)




![GUI](<img width="1902" height="892" alt="Screenshot 2025-07-23 003638" src="https://github.com/user-attachments/assets/67fb0dee-a6ad-4985-8ce8-798df1fa61a6" />)




![XGBoost Comparison](<img width="1119" height="668" alt="Screenshot 2025-07-23 003510" src="https://github.com/user-attachments/assets/a336aa12-aefa-4e5c-bf52-885f47fb8e88" />

)
