# Mobile Money Fraud Detection Model

A machine learning project focused on detecting fraudulent transactions in mobile money systems using advanced classification techniques.

## Project Overview

This project develops and implements a machine learning model to identify fraudulent transactions in mobile money platforms. Mobile money fraud is a significant challenge in financial technology, particularly in regions with high mobile money adoption. This model aims to enhance transaction security and protect users from unauthorized transactions.

## Features

- **Fraud Detection Model**: Advanced machine learning classifier trained on mobile money transaction data
- **Data Analysis**: Comprehensive exploratory data analysis (EDA) of transaction patterns
- **Feature Engineering**: Engineered features to capture fraudulent behavior patterns
- **Model Evaluation**: Multiple evaluation metrics to assess model performance
- **Synthetic Dataset**: Large-scale synthetic dataset representing real-world transaction scenarios

## Repository Structure

## Dataset

The project uses a **synthetic mobile money transaction dataset** containing:
- Transaction records with features relevant to fraud detection
- Target variable indicating fraudulent vs. legitimate transactions
- Real-world representative transaction patterns

**Dataset Size**: ~88 MB (CSV format)

## Notebook Contents

The main Jupyter notebook (`Fraud_detection_model_X_final.ipynb`) includes:

1. **Data Loading & Exploration**: Initial data inspection and statistical summaries
2. **Data Preprocessing**: Cleaning, missing value handling, and data transformation
3. **Exploratory Data Analysis (EDA)**: Visualization and analysis of transaction patterns
4. **Feature Engineering**: Creation of relevant features for fraud detection
5. **Model Development**: Training of classification models
6. **Model Evaluation**: Performance metrics and results analysis
7. **Visualization**: Insights and predictions visualization

## Technology Stack

- **Python**: Core programming language
- **Jupyter Notebook**: Development and documentation environment
- **Pandas & NumPy**: Data manipulation and numerical computing
- **Scikit-learn**: Machine learning algorithms and evaluation
- **Matplotlib & Seaborn**: Data visualization
- **XGBoost/LightGBM** (if used): Advanced gradient boosting models

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Required Python packages (see installation)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/OkwirFrances/Ml_MobileMoney_Fraud_Detection.git
cd Ml_MobileMoney_Fraud_Detection
