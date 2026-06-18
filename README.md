# Diabetes Prediction using Machine Learning

A Machine Learning project that predicts whether a person is diabetic or non-diabetic based on medical information using a Support Vector Machine (SVM) model.

## Project Overview

This project uses the PIMA Indians Diabetes Dataset to build a predictive system that can determine whether a person has diabetes based on several health-related attributes.

The model is trained using a Support Vector Machine (SVM) classifier and can make predictions for new patient data.

## Dataset Information

- Dataset: PIMA Indians Diabetes Dataset
- Total Records: 768
- Features: 8
- Target Classes:
  - 0 → Non-Diabetic
  - 1 → Diabetic

### Features Used

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-Learn
- Google Colab

## Machine Learning Workflow

1. Data Collection
2. Data Analysis
3. Feature and Label Separation
4. Data Standardization
5. Train-Test Split
6. Support Vector Machine (SVM) Training
7. Model Evaluation
8. Predictive System

---

## Project Screenshots

### 1. Dataset Overview

Viewing dataset samples and understanding feature columns.

![Dataset Overview](01-dataset-overview.png)

---

### 2. Data Standardization

Standardizing features using StandardScaler.

![Data Standardization](02-data-standardization.png)

---

### 3. Train-Test Split

Splitting the dataset into training and testing sets.

![Train Test Split](03-train-test-split.png)

---

### 4. Model Training

Training the Support Vector Machine classifier.

![Model Training](04-model-training.png)

---

### 5. Model Evaluation

Evaluating model performance using accuracy scores.

![Model Evaluation](05-model-evaluation.png)

---

### 6. Prediction System

Predicting whether a person is diabetic or non-diabetic based on input values.

![Prediction System](06-prediction-system.png)

---

## Model Used

### Support Vector Machine (SVM)

Support Vector Machine is a supervised machine learning algorithm used for classification tasks. It works by finding the optimal hyperplane that separates different classes in the feature space.

In this project, a Linear SVM classifier is used for binary classification.

## How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/Diabetes-Prediction-Using-Machine-Learning.git
```

### Install Dependencies

```bash
pip install numpy pandas scikit-learn
```

### Run the Project

```bash
python diabetes_prediction_using_machine_learning.py
```

## Repository Structure

```text
Diabetes-Prediction-Using-Machine-Learning/
│
├── Diabetes_Prediction_using_Machine_Learning.ipynb
├── diabetes_prediction_using_machine_learning.py
├── diabetes.csv
├── README.md
│Images
    ├── 01-dataset-overview.png
    ├── 02-data-standardization.png
    ├── 03-train-test-split.png
    ├── 04-model-training.png
    ├── 05-model-evaluation.png
    └── 06-prediction-system.png
```

## Key Learnings

- Data Preprocessing
- Data Standardization
- Feature Engineering
- Binary Classification
- Support Vector Machine (SVM)
- Model Evaluation
- Building Predictive Systems

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Feature Selection
- Streamlit Web Application
- Model Deployment

## Author

**Pranav Agneesh**

Day 2 of **#30Days30MLProjects**
