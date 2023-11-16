# MLB Pitcher Arsenal Optimization with XGBoost

## Overview

This project aims to optimize MLB pitcher arsenals by implementing Stuff+, Location+, and Pitching+ using XGBoost. The goal is to optimize and identify pitch metrics that contribute to swinging strikes, called strikes, and poor contact.

## Current Work

Currently, the project is focused on:

- **Model Training:** Implementing and fine-tuning the XGBoost model for pitch grades: retraining models after switching to SHAP feature importance.

## Next Steps

In the upcoming stages, the project will address the following tasks:

- **Model Analysis:** Finding the correlation of past-year pitch grades and next-year ERA.

Feel free to explore the code, data files, and visualizations in the respective folders to gain insights into the project's progress and outcomes.

**Note:** This README will be periodically updated to reflect the latest developments in the project.

## Project Structure

### 1. Code

The `code` folder contains all the source code for the project. Key scripts include:

- `models.py`: Handles data acquisition, data cleaning, and model implementation in class structures.
- `visualizations.py`: Creates visualizations of learned and tested data.

### 2. Graphs

The `graphs` folder holds visualizations and graphs generated during the training process and analysis. Key plot folders include:

- `correlation_matrices`: Correlation matrices of all the features in the cleaned datasets.
- `pitch_grade_feature_importance`: Visualization of the most important features identified by the XGBoost model for Stuff, Location, and Pitching grades.
- `pitch_type_effectiveness`: Graphs depicting the effectiveness of pitches when throw at different usage thresholds.

### 3. Models

The `models` folder stores trained models and model-related files. Key model folders include:

- `pitch_grade_models`: Folder containing text files of the Stuff, Location, and Pitching XGBoost models.
- `pitch_effectiveness_models`: Folder containing text files of the pitch and usage effectiveness XGBoost and Random Forest models.
