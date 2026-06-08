# Interest Rate Modelling using CIR and CIR++

This project implements the Cox-Ingersoll-Ross (CIR) interest rate model to reconstruct the yield curve using only the 3-month yield as input.

## Objectives
- Calibrate the CIR model using historical yield data
- Reconstruct yields across multiple maturities
- Evaluate out-of-sample predictive performance
- Implement and analyze a CIR++ extension

## Methodology
1. Data preprocessing and exploratory analysis
2. Yield curve visualization
3. CIR parameter calibration
4. Yield curve reconstruction
5. CIR++ extension using deterministic shift adjustments
6. Performance evaluation using R² metrics

## Results
- 6M R²: 0.9906
- 9M R²: 0.9531
- 1Y R²: 0.8770
- 2Y R²: 0.6082
- Overall Variance-Weighted R²: 0.9251

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Author
Vedika Goyal
