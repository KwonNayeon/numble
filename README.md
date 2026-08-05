# Small and Medium-sized Enterprises Closure Prediction Project

English | [한국어](README.ko.md)

## Project Summary

This project focuses on predicting the closure of small and medium-sized enterprises (SMEs) using Business Trends and Outlook Survey Data. Key aspects include:

- **Data Utilization:** Leveraged survey data to analyze and predict SME closures.
- **Machine Learning Models:** Implemented models using R, with packages such as `randomForest`, `catboost`, and `BART`.
- **Performance Evaluation:** Assessed models with metrics like AUROC, F1 score, and accuracy.
- **Key Findings:** Highlighted the importance of including non-financial data for accurate closure predictions.

## Key Results

| Method | AUROC | F1 score | Accuracy |
|---|---|---|---|
| Baseline | **0.556** | 0.964 | 0.940 |
| RF+ | 0.511 | 0.991 | 0.985 |
| CatBoost | 0.504 | **0.992** | **0.987** |
| BART | 0.536 | 0.977 | 0.961 |

- While CatBoost achieved the highest F1 score and accuracy, the baseline model actually showed the highest AUROC.
- This is likely due to class imbalance (the number of closed firms is much smaller than active firms), which can cause accuracy and F1 to overstate performance on the minority class.
- For this reason, we evaluated models using AUROC, F1, and accuracy together rather than relying on a single metric.
- Including non-financial variables improved predictive performance overall.

## Files Description

### `docs/`

- **`About the project in Korean.pdf`**: Comprehensive project documentation in Korean, covering the project overview, data details, ML models used, performance results, and key findings. Includes detailed preprocessing information.
- **`About the project.pdf`**: Summary of the project in English.
- **`Summary statistics.pdf`**: Contains summary statistics for the variables used in the analysis.
- **`Numble reflections.pdf`**: Reflections on the project, written in Korean, detailing insights and lessons learned.

### `code/`

- **`Numble Project.Rmd`**: R Markdown file with complete project code, from data preprocessing to model evaluation.
- **`Numble Project.R`**: R script with all code for data preprocessing, model training, and evaluation.

## Important Note

Due to a contract with the competition organization, the dataset used in this project cannot be uploaded. While the provided code will not include the dataset, it offers a comprehensive understanding of the project’s methodology and analysis.

## Contributors

- **Nayeon Kwon** - Sourcing non-financial data, data preprocessing, supporting building ML models, documentation
- **Younghoon Yoo** - Automated data preprocessing, building ML models, code optimization
