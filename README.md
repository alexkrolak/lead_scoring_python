# Lead Scoring Python

This repository provides a **Lead Scoring** solution using **Logistic Regression** in Python. The main focus is on refining and enhancing the original lead scoring process by adding **Exploratory Data Analysis (EDA)**, creating custom **User-Defined Functions (UDFs)**, and improving the overall code quality.

## Overview

The project aims to predict the probability that a lead will convert based on various features. The **Lead Scoring.ipynb** notebook serves as the core of the project and showcases the complete process, from data loading and cleaning to model scoring. The repository also highlights several key enhancements and edits made to the original code.

## Key Highlights

### 1. **Lead Scoring.ipynb**
   - **Main Focus**: This notebook is the heart of the project. It provides a step-by-step guide through the **Lead Scoring** process, which includes:
     - **Data Cleaning & Preparation**: Preprocessing the data to ensure it is ready for analysis and model building.
     - **Modeling**: Using **Logistic Regression** to create a lead scoring model.
     - **Model Evaluation**: Analyzing the model performance using various metrics.

### 2. **Exploratory Data Analysis (EDA) Edits**
   - The **EDA** has been significantly expanded to explore the dataset and identify important patterns. Changes include:
     - Visualizing distributions, outliers, and correlations to understand relationships.
     - Performing detailed feature analysis to improve lead scoring predictions.
     - Applying data transformation techniques and handling missing values more effectively.

### 3. **User-Defined Functions (UDFs)**
   - **Custom Functions**: Several UDFs were added to streamline the process:
     - Functions for **feature engineering** and **data transformations**.
     - **Scoring functions** that make it easier to calculate lead scores and update them as new data comes in.

### 4. **Code Refactoring**
   - The original script was refactored for **improved readability**, **modularity**, and **efficiency**. Key refactors include:
     - Clear separation of data processing, feature engineering, and modeling.
     - Improved error handling and logging for better code maintainability.

## Installation

To set up the project locally:

```bash
git clone https://github.com/alexkrolak/lead_scoring_python.git
cd lead_scoring_python
pip install -r requirements.txt
```

## Usage

1. Open the **`Lead Scoring.ipynb`** notebook in your Jupyter environment.
2. Run the cells sequentially to perform EDA, build the logistic regression model, and evaluate lead scores.
3. The final output will include visualizations and predictions.

## Future Improvements

- **Model Optimization**: Future work will focus on enhancing the model, experimenting with different algorithms, and tuning the hyperparameters for better performance.
- **Deployment**: The next step involves turning this notebook into a deployable solution that can score leads in real-time.
- **Automated Data Pipeline**: Automating the data preprocessing and scoring process for scalability.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
