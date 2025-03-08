# Graduate Admission Prediction

## Overview
This project predicts the probability of a student's admission into graduate school based on various factors such as GRE scores, TOEFL scores, CGPA, and research experience. It utilizes machine learning techniques to analyze patterns in the data and make predictions.

## Dataset
- **Source**: Kaggle Graduate Admissions Dataset
- **Features**:
  - GRE Score
  - TOEFL Score
  - University Rating
  - SOP (Statement of Purpose)
  - LOR (Letter of Recommendation Strength)
  - CGPA
  - Research Experience (0 or 1)
  - Chance of Admission (Target Variable)

## Dependencies
To run this project, install the required dependencies:
```bash
pip install numpy pandas matplotlib scikit-learn
```

## Setup & Execution
1. Clone or download the repository.
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook graduate-admission-prediction.ipynb
   ```
3. Follow the notebook cells to preprocess data, train models, and evaluate performance.

## Model Used
- **Regression Models** (e.g., Linear Regression, Random Forest, etc.)
- **Evaluation Metrics**: Mean Squared Error, R-Squared Score

## Results
- The model predicts the probability of admission with high accuracy.
- Performance is evaluated using regression metrics.

## Future Improvements
- Implement deep learning models for better accuracy.
- Deploy the model using Flask or FastAPI for real-time predictions.
