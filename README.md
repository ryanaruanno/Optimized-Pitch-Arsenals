# MLB Pitcher Arsenal Optimization with XGBoost

## Overview

This project aims to optimize MLB pitcher arsenals by implementing Stuff+, Location+, and Pitching+ using XGBoost. The goal is to optimize and identify pitch metrics that contribute to usage effectiveness.

Feel free to explore the code, data files, and visualizations in the respective folders to gain insights into the project's progress and outcomes.

**Note:** This README will be periodically updated to reflect the latest developments in the project.

## Current Work

Currently, the project is focused on:

- **Model Training and Algorithm Running:** Added fastest pitch data to the pitch grade models, so will retrain and reoptimize the entirety of 2022-2023.

## Next Steps

In the upcoming stages, the project will address the following task:

- **Github Updating:** Updating Github with the new code, graphs, and models.

## Project Structure

### 1. Code

The `code` folder contains all the source code for the project. Key scripts include:

- `models.py`: Handles data acquisition, data cleaning, and model implementation in class structures.
- `visualizations.py`: Creates visualizations of learned and tested data.

### 2. Graphs

The `graphs` folder holds visualizations and graphs generated during the training process and analysis. Key plot folders include:

- `correlations`: Correlation graphs for data visualizations.
- `pitch_grade_feature_importance`: Visualization of the most important features identified by the XGBoost model for Stuff, Location, and Pitching grades.
- `run_value_feature_importance`: Visualization of the most important features identified by the XGBoost model for Stuff, Location, and Pitching run value grades.

### 3. Models

The `models` folder stores trained models and model-related files. Key model folders include:

- `pitch_grade_models`: Folder containing text files of the Stuff, Location, and Pitching XGBoost models.
- `run_value_models`: Folder containing text files of the Stuff, Location, and Pitching run value XGBoost models.
