# 🏥 Automating Data Cleansing for Healthcare Records with NLP

This project uses **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques to automate the data cleansing of **Electronic Health Records (EHRs)**. It handles standardization of patient names, medical condition normalization, typo correction, and ensures consistency across records.

## 📁 Dataset

The dataset contains 55,500 patient records with fields such as:

- Name
- Age
- Gender
- Medical Condition
- Date of Admission
- Doctor
- Insurance Provider
- Medication
- Test Results

## 🔍 Project Goals

- ✅ Standardize patient names
- ✅ Normalize and correct medical conditions
- ✅ Train ML model to fix medical terminology errors
- ✅ Output a clean CSV file ready for downstream analytics

## ⚙️ Tech Stack

- Python
- Pandas
- scikit-learn
- NLP (TF-IDF Vectorization)

## 📦 How to Run

1. Clone the repository
2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `healthcare_cleaning.ipynb` in Jupyter Notebook
4. Run all cells
5. Check the `cleaned_healthcare_records.csv` output

## 📄 Output

A cleaned CSV with these columns:
 
- Name_Cleaned
- Medical_Condition_Cleaned
- Medical_Condition_ML_Predicted

## 🔗 Author

Created by Rashi"# healthcare-data-cleansing-nlp" 
"# healthcare-data-cleansing-nlp" 
