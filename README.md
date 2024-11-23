# 🧠 Operation Mind Shield: Decoding Alzheimer's

Welcome to **Operation Mind Shield**, data science challenge initiated by SuperDataScience focused on predicting Alzheimer's Disease based on patient data. This mission is designed for data scientists of all skill levels, with three different **Assignments** tailored to your expertise. Dive into the dataset, tackle the assignment that best matches your skills, and contribute to this collaborative project.

## 🛠 How to Contribute

Please read our CONTRIBUTING.md for guidelines on how to contribute.

## 📜 Mission Brief

In this mission, you will work with a dataset on Alzheimer's Disease patients. The goal is to build predictive models to determine the likelihood of a patient having Alzheimer's based on various features.

You'll progress through three phases depending on the assignment level you choose:
- **Data Cleaning & Analysis**
- **Data Preprocessing & Feature Selection**
- **Model Selection & Fine-Tuning**

## 🎯 Mission Objectives

- **Predict** whether a patient has Alzheimer's based on the available features.
- **Clean and preprocess** the data to improve the performance of your models.
- **Train models** that best suit your experience level, from simple to highly advanced.
- **Evaluate** your model's performance using appropriate validation techniques.
- **(Advanced Level Only)** Deploy your model using a **Streamlit App**.

## 🏆 Assignments

### 1. **Assignment 1: The Initiate** (Beginner Level)
- Perform **basic data cleaning**.
- Build a **simple linear model** (e.g., Logistic Regression).
- Evaluate your model with a **simple test set**.

### 2. **Assignment 2: The Specialist** (Intermediate Level)
- Conduct **elaborate data cleaning** with **1 feature selection step**.
- Train more advanced models like **Gradient Boosting**.
- Use **k-fold cross-validation** for evaluation.
- Perform basic **hyperparameter tuning**.

### 3. **Assignment 3: The Operative** (Advanced Level)
- Engage in **advanced data preprocessing** (looping feature selection and feature extraction using **PCA/LDA**).
- Build **ensemble models** using powerful frameworks (e.g., **SageMaker, Azure Machine Learning**).
- Perform extensive **hyperparameter tuning**.
- Evaluate using **k-fold cross-validation**.
- Deploy your model through a **Streamlit App**.

## The Dataset

- **PatientID:** A unique identifier assigned to each patient (4751 to 6900).
- **Age:** The age of the patients ranges from 60 to 90 years.
- **Gender:** Gender of the patients, where 0 represents Male and 1 represents Female.
- **Ethnicity:** The ethnicity of the patients, coded as follows:
    - 0: Caucasian
    - 1: African American
    - 2: Asian
    - 3: Other
- **EducationLevel:** The education level of the patients, coded as follows:
    - 0: None
    - 1: High School
    - 2: Bachelor's
    - 3: Higher
- **BMI:** Body Mass Index of the patients, ranging from 15 to 40.
- **Smoking:** Smoking status, where 0 indicates No and 1 indicates Yes.
- **AlcoholConsumption:** Weekly alcohol consumption in units, ranging from 0 to 20.
- **PhysicalActivity:** Weekly physical activity in hours, ranging from 0 to 10.
- **DietQuality:** Diet quality score, ranging from 0 to 10.
- **SleepQuality:** Sleep quality score, ranging from 4 to 10.
- **FamilyHistoryAlzheimers:** Family history of Alzheimer's Disease, where 0 indicates No and 1 indicates Yes.
- **CardiovascularDisease:** Presence of cardiovascular disease, where 0 indicates No and 1 indicates Yes.
- **Diabetes:** Presence of diabetes, where 0 indicates No and 1 indicates Yes.
- **Depression:** Presence of depression, where 0 indicates No and 1 indicates Yes.
- **HeadInjury:** History of head injury, where 0 indicates No and 1 indicates Yes.
- **Hypertension:** Presence of hypertension, where 0 indicates No and 1 indicates Yes.
- **SystolicBP:** Systolic blood pressure, ranging from 90 to 180 mmHg.
- **DiastolicBP:** Diastolic blood pressure, ranging from 60 to 120 mmHg.
- **CholesterolTotal:** Total cholesterol levels, ranging from 150 to 300 mg/dL.
- **CholesterolLDL:** Low-density lipoprotein cholesterol levels, ranging from 50 to 200 mg/dL.
- **CholesterolHDL:** High-density lipoprotein cholesterol levels, ranging from 20 to 100 mg/dL.
- **CholesterolTriglycerides:** Triglycerides levels, ranging from 50 to 400 mg/dL.
- **MMSE:** Mini-Mental State Examination score, ranging from 0 to 30. Lower scores indicate cognitive impairment.
- **FunctionalAssessment:** Functional assessment score, ranging from 0 to 10. Lower scores indicate greater impairment.
- **MemoryComplaints:** Presence of memory complaints, where 0 indicates No and 1 indicates Yes.
- **BehavioralProblems:** Presence of behavioral problems, where 0 indicates No and 1 indicates Yes.
- **ADL:** Activities of Daily Living score, ranging from 0 to 10. Lower scores indicate greater impairment.
- **Confusion:** Presence of confusion, where 0 indicates No and 1 indicates Yes.
- **Disorientation:** Presence of disorientation, where 0 indicates No and 1 indicates Yes.
- **PersonalityChanges:** Presence of personality changes, where 0 indicates No and 1 indicates Yes.
- **DifficultyCompletingTasks:** Presence of difficulty completing tasks, where 0 indicates No and 1 indicates Yes.
- **Forgetfulness:** Presence of forgetfulness, where 0 indicates No and 1 indicates Yes.
- **Diagnosis:** Diagnosis status for Alzheimer's Disease, where 0 indicates No and 1 indicates Yes.
- **DoctorInCharge:** This column contains confidential information about the doctor in charge, with "XXXConfid" as the value for all patients.

## Citation
When using free and open-source code or datasets, it is best practice to cite the material that you are using to give credits to the appropriate actors.

Please cite this dataset in your notebooks as follows:

**Title:** Alzheimer's Disease Dataset

**url:** https://www.kaggle.com/dsv/8668279

**DOI:** 10.34740/KAGGLE/DSV/8668279

**Publisher:** Kaggle

**Author:** Rabie El Kharoua

**Year:** 2024
