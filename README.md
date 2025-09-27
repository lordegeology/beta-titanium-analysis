# Beta Titanium Analysis

This repository contains various machine learning models and data analysis scripts for studying beta titanium properties. The project includes implementations of Artificial Neural Networks (ANN), Random Forest Regression (RFR), Support Vector Regression (SVR), Ridge Regression, and XGBoost models.

---

## Repository Structure
. ├── 150Cvalidationdata.csv # Validation data for the models ├── ANNforbetatitanium.ipynb # ANN implementation for beta titanium ├── modifiedzamodel.ipynb # Main data analysis and modeling notebook ├── RFRforbetatitanium.ipynb # Random Forest Regression implementation ├── Ridgeforbetatitanium.ipynb # Ridge Regression implementation ├── SVRforbetatitanium.ipynb # Support Vector Regression implementation ├── truedata.csv # Original dataset ├── validationdataplots.ipynb # Notebook for generating validation plots ├── XGBforbetatitanium.ipynb # XGBoost implementation └── .ipynb_checkpoints/ # Auto-saved checkpoints for notebooks

---

## Notebooks Overview

- **`modifiedzamodel.ipynb`**: The primary notebook for data preprocessing, feature engineering, and model fitting. It includes steps like plotting, regression analysis, and exporting results.
- **`ANNforbetatitanium.ipynb`**: Implements an Artificial Neural Network for predicting beta titanium properties.
- **`RFRforbetatitanium.ipynb`**: Uses Random Forest Regression for modeling.
- **`Ridgeforbetatitanium.ipynb`**: Applies Ridge Regression for analysis.
- **`SVRforbetatitanium.ipynb`**: Implements Support Vector Regression.
- **`XGBforbetatitanium.ipynb`**: Uses XGBoost for predictive modeling.
- **`validationdataplots.ipynb`**: Generates plots for validating the models.

---

## Data Files

- **`truedata.csv`**: The original dataset used for training and testing.
- **`150Cvalidationdata.csv`**: Validation dataset for model evaluation.

--- 

## Requirements

To run the notebooks, ensure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `matplotlib`
- `tensorflow`
- `scikit-learn`
- `xgboost`

---
### You can install the required libraries using:

```bash
pip install -r requirements.txt
```
--- 

## Usage
 - Clone the repository:

    - Open the desired notebook in Jupyter or any compatible IDE (e.g., Visual Studio Code).

    - Run the cells sequentially to execute the analysis or train the models.

---

## Results
The results of the analysis, including model predictions and validation plots, are saved as CSV files or displayed within the notebooks.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

-- 

## Acknowledgments
Special thanks to Prof. Suresh and Dr. Sandeep who provided the datasets and insights for this project.