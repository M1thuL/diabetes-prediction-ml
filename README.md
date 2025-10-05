# Diabetes Prediction

Simple machine-learning notebook that predicts diabetes (binary classification) from a CSV.

## Files
- `01 Diabetes Prediction [Supervised].ipynb` — main notebook (exploration, preprocessing, models)
- `diabetes.csv` — dataset file read by the notebook
- `requirements.txt` — Python packages needed
- `.gitignore` — ignore rules

## Dataset
- File location in the repo: `Datasets/diabetes.csv`  
- Typical columns used: `Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, Outcome`  
- `Outcome` is the binary target (0 = no, 1 = yes).

## How to run locally
1. Clone or download the repo.
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   # mac/linux
   source venv/bin/activate
   # windows (powershell)
   venv\Scripts\Activate.ps1
3. Install dependencies:
   Copy code
   pip install -r requirements.txt
4. Open the notebook:
   Copy code
   jupyter notebook "01 Diabetes Prediction [Supervised].ipynb"
