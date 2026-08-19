# Clinical Analysis of Ovarian Cancer Patients

## Project Overview

This project presents a clinical and statistical analysis of ovarian cancer patient data, with the objective of identifying factors associated with patient outcomes, treatment effectiveness, and survival.

The analysis was conducted as part of the AIBD course project and uses a consolidated clinical dataset along with derived subsets for specific research questions.

## Objectives

The project investigates ovarian cancer outcomes through multiple analytical perspectives:

- Identifying clinical and demographic factors associated with patient survival
- Analysing important features for predicting patient outcomes
- Studying the effectiveness of different cancer treatment approaches
- Exploring relationships between patient characteristics and clinical outcomes
- Identifying meaningful patient groups using data-driven analysis
- Deriving insights that can support clinical interpretation and decision-making

## Dataset

The project uses a consolidated ovarian cancer clinical dataset. Specific subsets of the main dataset were derived for individual research questions and analyses.

The dataset contains patient-level clinical attributes relevant to demographic characteristics, disease status, treatment, and outcomes.

> Dataset files are not included in this repository where the original source is externally hosted. Source links are provided separately where applicable.

## Analysis

### 1. Clinical and Survival Analysis

The project analyses patient survival and investigates the relationship between clinical variables and survival outcomes.

The analysis includes exploration of survival patterns and identification of factors associated with differences in patient outcomes.

### 2. Important Features for Survival Prediction

Feature-level analysis was performed to identify variables that contribute most strongly to predicting patient survival outcomes.

The analysis helps distinguish the clinical characteristics that have greater relevance to patient prognosis.

### 3. Cancer Treatment Effectiveness

Treatment-related variables were analysed to investigate differences in patient outcomes across treatment approaches.

The objective was to identify patterns in treatment effectiveness and understand how treatment-related factors relate to clinical outcomes.

### 4. Patient-Level Clinical Analysis

Patient characteristics and clinical variables were explored to identify relationships and patterns within the dataset.

Exploratory analysis and statistical techniques were used to understand the structure of the patient population and its outcomes.

### 5. Patient Grouping and Pattern Analysis

Data-driven analysis was used to explore whether patients could be grouped based on similarities in their clinical characteristics and outcomes.

This provides an additional perspective for understanding heterogeneity within the patient population.

### 6. Integrated Clinical Insights

The findings from the individual analyses were considered together to develop an overall understanding of the factors influencing ovarian cancer patient outcomes.

## Methodology

The overall workflow consisted of:

```text
Raw Clinical Dataset
        ↓
Data Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Feature Selection / Engineering
        ↓
Statistical & Predictive Analysis
        ↓
Survival / Treatment Analysis
        ↓
Patient-Level Pattern Analysis
        ↓
Clinical Insights
````

## Technologies

* **Python**
* **Pandas** — data manipulation and preprocessing
* **NumPy** — numerical computation
* **Matplotlib** — data visualization
* **Seaborn** — statistical visualization
* **Scikit-learn** — machine learning and feature analysis
* **Statistical / survival analysis techniques** — clinical outcome analysis
* **Jupyter Notebook** — analysis and experimentation

## Repository Structure

| File                                                        | Description                                                        |
| ----------------------------------------------------------- | ------------------------------------------------------------------ |
| `AIBD_FINAL_REPORT (2).pdf`                                 | Final project report containing the complete analysis and findings |
| `AIBD_PROJECT.ipynb`                                        | Primary project analysis notebook                                  |
| `AIBD_Final_Project.ipynb`                                  | Project analysis and modelling notebook                            |
| `AIBD_Final_Project-2.ipynb`                                | Additional project analysis notebook                               |
| `Important_features_for_predicting_the_survivability.ipynb` | Analysis of important features associated with survival            |
| `Analysis_of_Cancer_Treatment_Effectiveness.ipynb`          | Analysis of cancer treatment effectiveness                         |

## Key Outcome

The project integrates exploratory analysis, feature analysis, treatment-effectiveness analysis, and survival-oriented analysis to identify clinically relevant patterns in ovarian cancer patient data.

The resulting analyses provide a data-driven view of factors associated with patient outcomes and demonstrate the application of statistical and machine-learning techniques to clinical datasets.

## Data Sources

The original datasets and derived sub-datasets used in the project are documented in the final project report.

Where datasets are externally hosted, the corresponding source links are referenced rather than redistributed in this repository.

## Course

**AIBD — Analysis and Interpretation of Biological Data**

**Project:** Clinical Analysis of Ovarian Cancer Patients
