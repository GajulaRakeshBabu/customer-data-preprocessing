# Customer Data Preprocessing

This repository contains my solution for the customer data preprocessing assignment.

## Contents

- `customer_data_preprocessing.ipynb` – Jupyter notebook with:
  - Task 1: Cleaning the data (imputing missing values, removing duplicates)
  - Task 2: Encoding categorical columns (`city` with One-Hot Encoding, `gender` with Label Encoding)
  - Task 3: Scaling numerical features (`age`, `annual_income`) using Min-Max Scaling and Standardisation

## How to run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```

2. Open the notebook:
   - Using Jupyter Notebook:
     ```bash
     jupyter notebook customer_data_preprocessing.ipynb
     ```
   - Or upload the notebook to Google Colab and run all cells.

## Notes

- The notebook demonstrates:
  - Imputing missing values in `age` with the median and in `city` with the mode.
  - Removing duplicate rows.
  - Applying One-Hot Encoding to `city` and Label Encoding to `gender`.
  - Applying Min-Max Scaling and Standardisation to `age` and `annual_income`, with a short explanation of when to use each.
