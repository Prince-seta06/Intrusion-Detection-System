# Intrusion Detection System using Machine Learning

## Overview
This project implements an Intrusion Detection System (IDS) using machine learning techniques to identify malicious network activity.  
The goal is to classify network traffic as normal or intrusive based on extracted features.

The project is intended for academic and learning purposes and demonstrates a complete ML workflow including data preprocessing, model training, evaluation, and result analysis.

---

## Project Structure

ML_inno/
│
├── DATA/ # Raw datasets (ignored by git)
├── cleaned/ # Preprocessed datasets (ignored by git)
│
├── ML_Final.ipynb # Final model training and evaluation notebook
├── mlinno.ipynb # Experimental / intermediate notebook
├── README.md # Project documentation
├── .gitignore


---

## Features
- Data preprocessing and cleaning
- Feature selection and transformation
- Machine learning model training
- Model evaluation using standard metrics
- Clear separation between raw and processed data

---

## Technologies Used
- Python 3
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## Setup Instructions

1. Clone the repository

git clone https://github.com/Prince-seta06/Intrusion-Detection-System.git

cd Intrusion-Detection-System

2. (Optional) Create a virtual environment
python -m venv venv
venv\Scripts\activate


3. Install dependencies
pip install numpy pandas scikit-learn jupyter


4. Create required directories
Run the first cell of ML_Final.ipynb

## Usage

- Place raw datasets inside the `DATA` directory
- Run preprocessing steps to generate cleaned data in `cleaned`
- Open and run `ML_Final.ipynb` for final training and evaluation

---

## Notes
- The `DATA` and `cleaned` folders are intentionally excluded from version control
- Only notebooks, code, and documentation are tracked
- This avoids committing large or sensitive datasets

---
