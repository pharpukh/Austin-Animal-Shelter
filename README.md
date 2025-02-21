# Exploratory Data Analysis - Austin Animal Shelter

## Overview
This project is a university assignment focused on **Exploratory Data Analysis (EDA)** of intake and outcome records from the Austin Animal Center in Texas, USA. The objective is to **clean the data, analyze trends, and visualize relationships** between various features to extract meaningful insights.

## Dataset
The project is based on the following datasets from the **[Austin Open Data Portal](https://data.austintexas.gov/)**:

### Intakes (`intakes.csv`)
- Records of animals taken into the shelter from **October 1, 2013, to October 6, 2024**.

### Outcomes (`outcomes.csv`)
- Records of animals leaving the shelter (adopted, returned to the owner, etc.) within the same time period.

### (Optional) Locations (`locations.csv`)
- Records of stray dogs and cats found within the last **seven days**, some of which are housed at volunteers' homes.

## Key Features
- **Animal Type** - Type of animal (Dog, Cat, Other)
- **Breed** - Breed of the animal
- **Age upon Intake** - Age of the animal when admitted
- **Intake Type** - How the animal entered the shelter
- **Outcome Type** - How the animal left the shelter
- **DateTime** - Date and time of intake or outcome

More details can be found in the **official data sources** linked above.

## Project Structure
```
├── assignment01.ipynb    # Jupyter Notebook with EDA analysis
├── intakes.csv           # Intake dataset (if available)
├── outcomes.csv          # Outcome dataset (if available)
├── locations.csv         # (Optional) Locations dataset
├── README.md             # Documentation
```

## Requirements
To run this project, install the following dependencies:
```sh
pip install pandas numpy matplotlib seaborn
```

## How to Run
1. **Download the datasets** from the links provided above or place `intakes.csv` and `outcomes.csv` in the project directory.
2. **Open Jupyter Notebook**:
   ```sh
   jupyter notebook
   ```
3. **Run `assignment01.ipynb`** step by step, following the markdown explanations.

## Tasks Completed

### 1. Data Cleaning & Preprocessing
- Handling missing values
- Converting categorical features
- Transforming date-related data
- Removing duplicates

### 2. Descriptive Statistics & Visualization
- Analysis of `Age upon Intake` and `DateTime`
- Univariate and bivariate statistics on key features
- Correlation analysis

### 3. Answering Key Questions
- Is the type of animal intake related to the type of outcome?
- Does age influence adoption rates?
- Are there seasonal trends in animal intake?

### 4. Custom Questions & Insights
- Additional analysis beyond the given task requirements
- Exploration of external datasets for deeper insights

## Evaluation
The analysis uses:
- **Visualizations** to support insights
- **Descriptive statistics** to summarize data
- **Interpretation of trends** to extract meaningful conclusions

## Author
Farukh Rustamov

