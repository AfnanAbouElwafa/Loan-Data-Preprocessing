# Loan Data Preprocessing

This project focuses on preprocessing and cleaning loan data using the NumPy library. The goal is to make the data suitable for machine learning projects.

## Dataset Description

The loan data used in this project pertains to loan applications in the United States in 2015. Each application includes the following information:

- Issue Date
- Loan Status
- Term
- Grade
- Sub-grade
- Verification Status
- Address State
- Funded Amount
- Loan Amount
- Interest Rate
- Total Payment
- Installment

## Project Phases

1. Dataset Splitting: The dataset is split into numerical and string data for further processing.
2. Checkpoints: Checkpoints are created at various stages to track progress during preprocessing.
3. String Column Manipulation: String columns are manipulated to ensure they are in a suitable format for analysis. Missing values in string columns are also addressed.
4. String to Numeric Conversion: String columns are converted into numeric values to facilitate machine learning algorithms.
5. Checkpoint 1: Checkpoint 1 is reached after completing the manipulation of the string columns.
6. Numeric Column Manipulation: Numeric columns are manipulated in various ways, and missing values in numeric columns are addressed.
7. Checkpoint 2: Checkpoint 2 is reached after the manipulation of the numeric columns.
8. Creating the "Complete" Dataset: The processed numeric and string columns are combined to create the "complete" dataset.
9. Dataset Storage: The new dataset is stored for future use.


