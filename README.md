# Healthcare Cost Prediction using Regression

This project predicts **healthcare costs (expenses)** using a **regression model** on a dataset containing personal and medical information. The goal is to predict healthcare expenses with a **Mean Absolute Error (MAE) under 3500** to pass the challenge.  

This notebook is designed for **FreeCodeCamp Machine Learning Certification Challenge**.

---

## Project Files

- `fcc_predict_health_costs_with_regression.ipynb` – Jupyter Notebook containing:
  - Data preprocessing
  - Train-test split
  - Regression model creation using a neural network
  - Training and evaluation
  - Predictions and visualization
- `README.md` – Project description and instructions

---

## Dataset

The dataset (`insurance.csv`) contains the following features:

| Column   | Description                               |
|----------|-------------------------------------------|
| age      | Age of the insured person                  |
| sex      | Gender of the insured (male/female)       |
| bmi      | Body mass index                            |
| children | Number of children covered by health plan |
| smoker   | Whether the person smokes (yes/no)        |
| region   | Residential area (northeast, southeast...)|
| expenses | Yearly medical expenses (target variable) |

---

## How to Run

### Option 1: Run in Google Colab (Recommended)

1. Open `fcc_predict_health_costs_with_regression.ipynb` in Google Colab.
2. Run all cells sequentially:
   - Install any missing packages (Colab usually has `pandas`, `numpy`, `scikit-learn`, `tensorflow`, `matplotlib` preinstalled).
   - Load dataset (the notebook downloads `insurance.csv` automatically).
   - Preprocess the data, create and train the regression model.
3. Run the final cell to check if your model passes the challenge (MAE < 3500).  
4. Optionally, visualize predictions using the scatter plot in the last cell.  

**Note:** Make sure to enable **link sharing** if submitting the Colab link.

---

### Option 2: Run Locally (Jupyter Notebook / VSCode / Anaconda)

1. **Clone or download** this repository to your local machine.
2. Install required Python libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn tensorflow
