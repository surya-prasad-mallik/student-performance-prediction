# Student Performance Prediction

A machine-learning project exploring how student and academic-related attributes relate to exam scores. The repository includes a Jupyter notebook for data preparation, exploratory analysis, model training, and evaluation.

## Project overview

The dataset includes fields such as gender, parental education, lunch type, test preparation, and math, reading, and writing scores. The notebook can be used to inspect the data, prepare features, train regression models, and compare evaluation metrics.

## Models and evaluation

Models described in this project:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Evaluation metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² score

Actual performance depends on the data split, preprocessing, and model configuration. Run the notebook to see the measured results; no specific accuracy claim is made here.

## Tech stack

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn

## Project structure

```text
Student-Performance-ML/
├── data/
│   └── Students Performance.csv
├── notebooks/
│   └── student_performance_ml_project.ipynb
└── README.md
```

The paths above describe the intended project layout; check the repository files for the current exact structure.

## Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/surya-prasad-mallik/student-performance-prediction.git
   cd student-performance-prediction
   ```

2. Create and activate a virtual environment:

   Windows PowerShell:
   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

   macOS/Linux:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Install the packages used by the notebook:

   ```bash
   python -m pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

4. Start Jupyter:

   ```bash
   jupyter notebook
   ```

5. Open the project notebook and run its cells in order. If the dataset is stored elsewhere, update the notebook's data path accordingly.

## Future improvements

- Add a reproducible dependency file
- Document measured model results and the evaluation setup
- Add clear plots and explain the most useful findings
- Validate predictions on a held-out test set

## Author

**Surya Prasad Mallik**
