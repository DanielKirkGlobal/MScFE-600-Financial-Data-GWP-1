# MScFE 600 Financial Data Group Work Project #1

**WorldQuant University - MSc Financial Engineering Program**

## Project Overview

This repository contains a comprehensive financial data analysis project demonstrating advanced quantitative finance techniques across four key areas:

1. **Data Quality Assessment** - KYC data analysis with quality metrics
2. **Yield Curve Modelling** - Japanese Government Bond analysis using Nelson-Siegel and Cubic-Spline methods
3. **Correlation & PCA Analysis** - Multi-market government securities analysis across London, New York, Shanghai, Hong Kong, and Tokyo
4. **ETF Portfolio Analysis** - XLK Technology Select Sector SPDR Fund analysis with PCA and SVD decomposition

## Project Structure

```
MScFE-600-Financial-Data-GWP-1/
├── notebooks/
│   ├── task1_data_quality.ipynb          # KYC Data Quality Analysis
│   ├── task2_yield_curve_modeling.ipynb  # Japanese Yield Curve Modelling
│   ├── task3_correlation_pca.ipynb       # Five-Market Correlation & PCA
│   └── task4_etf_analysis.ipynb          # XLK ETF Analysis with PCA/SVD
├── PROJECT_TESTING_REPORT.md             # Comprehensive testing results
├── requirements.txt                      # Python dependencies
└── README.md                             # This file
```

## Technical Implementation

### Task 1: Data Quality Assessment
- **Focus**: KYC (Know Your Customer) data analysis
- **Techniques**: Missing value analysis, duplicate detection, data type validation
- **Output**: Comprehensive data quality metrics and recommendations

### Task 2: Yield Curve Modelling
- **Focus**: Japanese Government Bond yield curve analysis
- **Techniques**: Nelson-Siegel parametric model, Cubic-Spline interpolation
- **Output**: Model comparison, parameter estimation, economic interpretation

### Task 3: Correlation and Principal Component Analysis
- **Focus**: Government securities from five major financial markets
- **Markets**: London, New York, Shanghai, Hong Kong, Tokyo
- **Techniques**: Correlation analysis, PCA, dimensionality reduction
- **Output**: Factor structure identification, variance decomposition

### Task 4: ETF Portfolio Analysis
- **Focus**: XLK - Technology Select Sector SPDR Fund
- **Techniques**: Returns analysis, covariance modelling, PCA, SVD
- **Output**: Mathematical equivalence demonstration, portfolio risk analysis

## Key Technologies

- **Python 3.13+** - Core programming language
- **pandas & numpy** - Data manipulation and numerical computing
- **matplotlib & seaborn** - Data visualisation
- **scipy** - Scientific computing and optimisation
- **scikit-learn** - Machine learning and statistical analysis
- **Jupyter Notebooks** - Interactive development environment

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/MScFE-600-Financial-Data-GWP-1.git
   cd MScFE-600-Financial-Data-GWP-1
   ```

2. **Create virtual environment:**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```

## Academic Standards

This project adheres to:
- **WorldQuant University** academic formatting standards
- **Professional quantitative finance** methodologies
- **Comprehensive documentation** and analysis

## Key Findings

- **Data Quality**: Demonstrated systematic approach to identifying and addressing financial data quality issues
- **Yield Curve Modelling**: Successfully implemented and compared parametric vs. non-parametric yield curve fitting methods
- **Multi-Market Analysis**: Revealed factor structures underlying international government securities markets
- **ETF Analysis**: Proved mathematical equivalence of PCA and SVD decomposition methods in portfolio analysis

## Mathematical Techniques Demonstrated

- **Nelson-Siegel Yield Curve Model**: Parametric curve fitting with economic interpretation
- **Principal Component Analysis**: Dimensionality reduction and factor identification
- **Singular Value Decomposition**: Matrix factorisation and mathematical equivalence
- **Correlation Analysis**: Cross-market relationship quantification
- **Portfolio Theory**: Risk-return analysis and diversification benefits

## Academic Context

This project represents advanced coursework in the MSc Financial Engineering program, demonstrating practical application of quantitative finance theory to real-world financial data analysis challenges.

## Author

**MSc Financial Engineering Students**  
WorldQuant University  
October 2025

---

*This project demonstrates proficiency in advanced quantitative finance techniques and serves as a comprehensive example of modern financial data analysis methodologies.*
