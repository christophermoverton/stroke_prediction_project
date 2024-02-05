# Stroke Prediction Project

## Overview
This project focuses on building a stroke prediction model using R. The goal is to explore and analyze a dataset containing patient information to predict the likelihood of stroke. Various classification algorithms are implemented, with a detailed analysis of the chosen model. The project includes steps for data preprocessing, model building, evaluation, and deployment.

## Project Structure
- **Data Analysis Report (RMarkdown):** Contains detailed analysis steps, code, and visualizations.
- **Model Deployment (Plumber & Vetiver):** Utilizes plumber for API creation and vetiver for model storage.
- **Findings and Conclusions:** Summarizes key findings, strengths of the chosen model (K-Nearest Neighbors), and recommendations for ongoing improvements.

## Usage
1. Open and run the RMarkdown file for comprehensive data analysis.
2. Explore the Plumber API for model deployment using the specified endpoints.
3. Refer to the Findings and Conclusions section for insights and recommendations.

## Dependencies
Ensure that the required R packages (tidyverse, caret, etc.) are installed. Use the following commands for installation:
```R
install.packages(c("tidyverse", "caret", "plumber", "vetiver"))
