# Household Financial Vulnerability Prediction

<p align="center">
  <strong>A Deep Learning Approach to Understanding and Predicting Household Financial Vulnerability</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Status-In%20Progress-orange" alt="Project Status">
  <img src="https://img.shields.io/badge/Project-Data%20Analytics-green" alt="Project Type">
</p>

## Project Overview

This project investigates the relationship between household demographic characteristics, income and financial circumstances, with the aim of understanding and predicting household financial vulnerability.

Using data from the **Bank of England's NMG Household Survey**, the project applies exploratory data analysis (EDA), data preparation and machine learning techniques to identify patterns within household financial data.

A particular focus is placed on evaluating whether deep learning can effectively predict indicators of financial vulnerability, and how its performance compares with more traditional machine learning approaches.

The project forms part of the **COM6035M Data Analytics** module at York St John University.

## Research Objectives

The investigation is guided by three research questions:

1. **What relationships exist between household demographic characteristics, income and financial circumstances?**
2. **Which demographic and economic characteristics are most strongly associated with household financial vulnerability?**
3. **To what extent can a deep learning model predict household financial vulnerability compared with traditional machine learning approaches?**

## Dataset

| Detail | Description |
|---|---|
| Dataset | NMG Household Survey |
| Source | Bank of England |
| Study period | September 2026 |
| Data type | Household survey data |
| Structure | Cross-sectional |
| Format | Excel / CSV |

The dataset contains household-level survey information covering demographic and financial characteristics.

The September 2026 survey wave is being used as the primary dataset for this investigation. This provides a snapshot of household financial circumstances, allowing relationships between demographic and economic variables to be explored.

*Note: The original dataset is not included in this repository. Data access and usage should follow the relevant Bank of England terms.*

## Methodology

The project follows a structured data analytics workflow.

### 1. Data Exploration

- Inspect dataset dimensions, structure and variable types.
- Examine missing values and potential inconsistencies.
- Analyse distributions of demographic and financial variables.
- Identify relationships and patterns between relevant features.
- Investigate the distribution of the selected financial vulnerability outcome.

### 2. Data Preparation

- Select relevant variables based on the research objectives.
- Handle missing values appropriately.
- Encode categorical variables.
- Scale numerical features where required.
- Engineer features where justified.
- Prepare training and testing datasets.

### 3. Model Development

The investigation will compare deep learning against traditional machine learning approaches.

| Model | Purpose |
|---|---|
| Logistic Regression | Traditional statistical classification baseline |
| Random Forest | Non-linear ensemble learning baseline |
| Multi-Layer Perceptron (MLP) | Deep learning classification model |

### 4. Model Evaluation

Models will be evaluated using appropriate classification metrics, potentially including:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- ROC-AUC
- Precision-Recall AUC

Particular attention will be paid to class imbalance and the trade-off between false positives and false negatives.

### 5. Analysis and Discussion

The final stage will interpret the findings in relation to the research questions, assess the effectiveness of the models, and critically discuss limitations, reliability and potential real-world applications.

## Technologies and Libraries

The project uses Python and its data science ecosystem.

| Technology | Application |
|---|---|
| Python | Main programming language |
| Jupyter Notebook | Interactive analysis and experimentation |
| Pandas | Data manipulation and preparation |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Scikit-learn | Traditional machine learning and evaluation |
| TensorFlow / Keras | Deep learning model development |

## Repository Structure

```text
household-financial-vulnerability/
│
├── data/
│   ├── original/          # Original survey data
│   └── processed/         # Prepared datasets
│
├── notebooks/
│   ├── 01_data_discovery.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_data_preparation.ipynb
│   └── 04_model_development.ipynb
│
├── presentation/          # Project presentation materials
│
├── results/               # Model outputs and visualisations
│
├── README.md
└── requirements.txt
```

## Getting Started

### Prerequisites

- Python 3.10 or later
- Jupyter Notebook or JupyterLab
- Access to the original survey dataset

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/household-financial-vulnerability.git
```

Navigate into the project directory:

```bash
cd household-financial-vulnerability
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment:

**Windows**
```bash
venv\Scripts\activate
```

**macOS / Linux**
```bash
source venv/bin/activate
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

## Project Progress

- [x] Research topic selected
- [x] Initial dataset identified
- [x] Research questions established
- [ ] Dataset extraction and inspection
- [ ] Exploratory data analysis
- [ ] Data cleaning and preparation
- [ ] Feature engineering
- [ ] Traditional machine learning models
- [ ] Deep learning model development
- [ ] Model evaluation and comparison
- [ ] Final analysis and conclusions

## Limitations

The investigation will consider several potential limitations:

- Survey responses may contain missing, incomplete or self-reported information.
- The dataset represents a particular survey period and may not capture changes over time.
- The selected financial vulnerability outcome may only represent one aspect of wider household financial vulnerability.
- Class imbalance may affect the reliability of classification metrics.
- Model performance does not necessarily imply causal relationships between household characteristics and financial vulnerability.

## Academic Context

**Module:** COM6035M – Data Analytics  
**Institution:** York St John University  
**Academic Year:** 2026/27  
**Project Type:** Independent Data Analytics Investigation

---

<p align="center">
  <i>Exploring the relationship between household characteristics and financial vulnerability through data analytics and machine learning.</i>
</p>
