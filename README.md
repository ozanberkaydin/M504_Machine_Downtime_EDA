# M504 Machine Downtime EDA

This repository contains my individual project for M504 AI and Applications.

## Project Title

Exploratory Data Analysis of Machine Downtime Using Python

## Files

* `M504_Machine_Downtime_EDA.ipynb` : Original Jupyter Notebook
* `M504_Machine_Downtime_EDA.html` : Exported HTML report
* `machine_downtime.csv` : Dataset used in the project
* `requirements.txt` : Required Python libraries

## Dataset

The dataset used in this project is a machine downtime dataset containing operational and sensor measurements from manufacturing equipment.

The notebook loads the dataset using:

```python
df = pd.read_csv("machine_downtime.csv")
```

## How to Run

1. Download or clone this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open `M504_Machine_Downtime_EDA.ipynb` in Jupyter Notebook or VS Code.
4. Run all cells from top to bottom.

## Main Methods Used

* Data Cleaning
* Missing Value Analysis
* Descriptive Statistics
* Grouped Analysis
* Crosstab Analysis
* Correlation Analysis
* Pivot Tables
* Data Visualization with Matplotlib and Seaborn
* Business-Oriented Exploratory Data Analysis

## Key Findings

* Hydraulic pressure showed a strong relationship with machine downtime.
* Higher spindle speed was associated with increased downtime risk.
* Pressure and torque combinations revealed high-risk operating conditions.
* Seasonal and machine-specific patterns were identified through exploratory analysis.

## Author

Ozan Berk Aydin

M504 – AI and Applications
