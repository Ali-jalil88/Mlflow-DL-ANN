# Mlflow-DL-ANN
# Gender Classification Using ANN with MLflow

## 1. Overview of the Dataset

### Dataset Description:
The dataset contains biometric or behavioral data (e.g., height, weight, voice pitch) for predicting gender. The task is binary classification: **Gender**.

### Features:
- **Height (cm)**
- **Weight (kg)**
- **Voice_Pitch**
- Other relevant features...

### Target Variable:
- **Gender**
  - `0 = Male`
  - `1 = Female`

### Dataset Split:
- **Training Set**: 70%  
- **Validation Set**: 15%  
- **Test Set**: 15%

---

## 2. Objective
Develop and train an **Artificial Neural Network (ANN)** for classifying gender, utilizing **MLflow** to track and manage the experiment.

---

## 3. Experiment Workflow

### Data Preprocessing

#### Handle Missing Values:
- Impute missing data with **mean** or **median** for numeric features.

#### Feature Scaling:
- Normalize numeric features using `StandardScaler`.

#### Data Splitting:
- Split the dataset into **training**, **validation**, and **test** sets.
