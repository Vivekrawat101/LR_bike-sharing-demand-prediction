# Bike Sharing Demand Prediction

This repository contains my submission for the **Bike Sharing Demand Prediction** assignment. The objective is to build a multiple linear regression model to predict bike demand using various factors. This project covers data preparation, model building, and evaluation.

## Problem Statement

BoomBikes, a US-based bike-sharing company, saw a revenue drop during the COVID-19 pandemic. To bounce back, they need to understand what drives bike demand. This project models those factors to help them plan for the future.

## Repository Structure

- **`Bike_Sharing_Assignment.ipynb`**: The Jupyter notebook with data preparation, analysis, model building, and results.
- **`subjective_questions.pdf`**: Answers to the assignment's subjective questions on linear regression.
- **`data/`**: Dataset folder.
- **`README.md`**: Overview of the project and instructions.

## Getting Started

### Prerequisites

You'll need Python and these libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install them with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn 
```

### Running the Notebook

Clone the repository:

```bash
git clone https://github.com/yourusername/bike-sharing-demand-prediction.git
```
Navigate to the project directory:

```bash
cd bike-sharing-demand-prediction
```

Open the Jupyter notebook:

```bash
jupyter notebook Bike_Sharing_Assignment.ipynb
```

## Model Evaluation
The model's effectiveness is measured by the R-squared value, indicating how well the independent variables explain the target (cnt).

## Results
The model highlights key factors like weather, seasons, and trends that influence bike demand, helping BoomBikes plan their strategy.

## Acknowledgments
This project was created as part of a linear regression assignment in the Post Graduate Program in Data Science and ML at IIIT Bangalore. Thanks to the instructors and peers for their support.
