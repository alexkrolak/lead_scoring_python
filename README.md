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
