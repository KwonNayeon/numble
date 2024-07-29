<<<<<<< HEAD
<<<<<<< HEAD
# Small and Medium-sized Enterprises Closure Prediction Project

## Project Summary

This project focuses on predicting the closure of small and medium-sized enterprises (SMEs) using Business Trends and Outlook Survey Data. Key aspects include:

- **Data Utilization:** Leveraged survey data to analyze and predict SME closures.
- **Machine Learning Models:** Implemented models using R, with packages such as `randomForest`, `catboost`, and `BART`.
- **Performance Evaluation:** Assessed models with metrics like AUROC, F1 score, and accuracy.
- **Key Findings:** Highlighted the importance of including non-financial data for accurate closure predictions.

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

Feel free to explore the repository and download the PDFs for detailed information about the Small and Medium-sized Enterprises Closure Prediction Project.
=======
# urban-parks-childrens-happiness
>>>>>>> 1fbd89d (Initial commit)
=======
# Causal Effect of Urban Parks on Children’s Happiness

## Overview
This repository contains the thesis titled "Causal Effect of Urban Parks on Children’s Happiness," including data, results, and code.

## Repository Structure
- `thesis/`: Contains the main thesis document, abstract, individual chapters, and references.
- `data/`: Contains raw and processed datasets used in the analysis.
- `results/`: Contains figures and tables generated from the analysis.
- `award/`: Contains documents related to the awards and recognitions received for this work.
- `code/`: Contains R scripts and notebooks for data preprocessing, analysis, and creating plots.

## Getting Started
1. Clone the repository:
    ```bash
    git clone https://github.com/KwonNayeon/urban-parks-childrens-happiness.git
    ```
2. Navigate to the project directory:
    ```bash
    cd urban-parks-childrens-happiness
    ```

## Dependencies

To run the R scripts and analysis, you need the following R packages:

- `ggdag` (For plotting Directed Acyclic Graphs)
- `MatchIt`
- `ggplot2`
- `sensitivityfull`
- `sensitivitymw`
- `lmtest` (For `coeftest`)
- `sandwich` (For `vcovCL`)
- `tidyverse` (Includes `dplyr` and other packages)

You can install these packages in R using the following command:
```r
install.packages(c("ggdag", "MatchIt", "ggplot2", "sensitivityfull", "sensitivitymw", "lmtest", "sandwich", "tidyverse"))
```
### Notes

The above list includes only some of the packages used in the analysis. Other packages may also be required for specific functionalities or scripts.

If you encounter errors related to missing packages, please refer to the script's `library()` calls to identify any additional packages that may need to be installed.

For a complete list of packages, refer to `main_analysis.Rmd` in the code folder or contact me for assistance.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or comments, please contact [nayeonkn0330@gmail.com].
>>>>>>> 4a53286 (Update README.md)
