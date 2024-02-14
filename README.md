# Assignment-1: Correlation Analysis of Two Matrices

## Author
Asra Tasneem Shaik

## Date
02-14-2024

## Programming Language & Version
Python [3.8]

## Dependencies
- pandas 
- numpy 
- seaborn 
- matplotlib 
- scipy 

## Input
- Two CSV files containing the matrices: `matrix1.csv` and `matrix2.csv`

## Short Script Description
This Python script calculates the correlation matrices for two datasets (`matrix1.csv` and `matrix2.csv`), creates heatmap plots using seaborn, and finally computes the Pearson correlation between the original matrices.

The script performs the following steps:
1. Initially imports necessary libraries: pandas, numpy, seaborn, matplotlib, scipy.
2. Loads the datasets `matrix1.csv` and `matrix2.csv` into DataFrame variables.
3. Calculates the correlation matrices for both datasets and rounds the correlation coefficients to two decimal places.
4. Creates heatmap plots of the correlation matrices using seaborn, with annotations.
5. Computes the Pearson correlation between the original matrices.

## Output Files
- Two heatmap plots: one for each correlation matrix (`Matrix1.png` and `Matrix2.png`)
- Pearson correlation between the original matrices (`Pearson_Correlation.txt`)
