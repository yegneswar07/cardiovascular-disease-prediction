# Cardiovascular Disease Prediction

This project analyzes the factors contributing to heart disease using a dataset of 70,000 patient records. It employs various machine learning algorithms to predict the presence of cardiovascular disease.

## Project Structure
- **`Cardiovascular_Prediction.ipynb`**: The main Jupyter Notebook containing all code for:
  - Data Loading & Cleaning (handling outliers, duplicates)
  - Feature Engineering (Calculating BMI)
  - Exploratory Data Analysis (EDA) with visualizations
  - Model Training & Evaluation (SVM, KNN, Decision Tree, Logistic Regression, Random Forest)
- **`cardio_train (1).csv`**: The input dataset (semicolon-separated).

## Key Findings
- **Feature Importance**: Systolic blood pressure (`ap_hi`) and Cholesterol levels significantly show correlation with heart disease.
- **BMI**: Added as a derived feature to improve prediction accuracy.

## Models Evaluated
We benchmarked the following algorithms:
1.  **Logistic Regression**
2.  **K-Nearest Neighbors (KNN)**
3.  **Decision Tree**
4.  **Random Forest**
5.  **Support Vector Machine (SVM)**

## How to Run
1.  Ensure you have Python installed with the following libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```
2.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
3.  Open `Cardiovascular_Prediction.ipynb` and run all cells.

## Results

## License

This project is licensed under the MIT License.

MIT License

